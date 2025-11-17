# Canzonetta sull'aria
"Sull'aria ... che soave zeffiretto" in Mozart's Le nozze di Figaro, arranged for Minecraft's noteblocks.

Recording: https://youtu.be/2ZWYiuBa7NQ

## Arrangement
Instrumentation:
* Susanna: bell + flute
* La Contessa: harp + flute
* Oboe: flute
* Bassoon: iron xylophone
* Violin I & II, viola: harp
* Cello: bass

Tranposed up one semitone to better fit noteblock's ranges. However, a few notes still do not fit, then they are either transposed up/down an octave or played by a different instrument, depending on which sounds better to me.

## Play requirements
Minecraft Java 1.20 to play the pre-built world; 1.19+ if you build from source.

Either way, go to Music & Sounds settings and turn on Directional Audio. Optionally, turn down Master Volume to about 60% to 70%, otherwise it might be a bit too loud (but of course this depends on your speakers).

## Easy install 
Copy the [World](https://github.com/FelixFourcolor/Canzonetta-sull-aria/tree/main/World) folder into your saves.

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

## Build from source
### Build requirements
* python 3.10-3.12
* pip

### Overview of the build process
The structure is auto-generated using [noteblock-generator](https://pypi.org/project/noteblock-generator/0.2.1). The program takes [src](https://github.com/FelixFourcolor/Canzonetta-sull-aria/tree/main/src) which defines the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install noteblock-generator 0.2.1 (must be this exact version):
    ```sh
    pip install "noteblock-generator==0.2.1"
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain [src](https://github.com/FelixFourcolor/Canzonetta-sull-aria/tree/main/src). You may clone the repo or download just that folder.

3. Obtain a world in Minecraft Java 1.19+. You may use your existing world or create a new one.

4. Run:
    ```
    noteblock-generator [path to src] [path to minecraft world]
    ```

    See [noteblock-generator](https://pypi.org/project/noteblock-generator/0.2.1) for more build options.
