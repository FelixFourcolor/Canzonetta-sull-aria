# Canzonetta sull'aria
"Canzonetta sull'aria" in Mozart's Le nozze di Figaro, arranged for Minecraft's noteblocks.

Recording: https://youtu.be/Xl7S07r3emA

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
Minecraft java 1.20+ if you play the pre-built world, 1.19+ if you build from source.

Either way, go to Music & Sounds setting, turn on Directional Audio and turn down Jukebox/Note Blocks sound level to 70%.

## Easy install 
Copy the [World](https://github.com/FelixFourcolor/Canzonetta-sull-aria/tree/main/World) folder into your saves.

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

## Build from source
### Build requirements
* python 3.10+
* pip

### Overview of the build process
The structure is auto-generated using [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator). The program takes [src](https://github.com/FelixFourcolor/Canzonetta-sull-aria/tree/main/src) which defines the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install the lastest version of [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator):
    ```
    pip install --upgrade noteblock-generator
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain [src](https://github.com/FelixFourcolor/Canzonetta-sull-aria/tree/main/src). You may clone the repo or download just that folder.

3. Obtain a world in Minecraft java 1.19+. You may use your existing world or create a new one.

4. If you are inside the world, exit it first. Then,
    ```
    noteblock-generator [path to src] [path to minecraft world]
    ```

    (See [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator)'s documentation for explanation and more build options.)
