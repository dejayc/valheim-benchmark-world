# valheim-benchmark-world
A world file to benchmark frames per second (FPS) for the PC survival game Valheim.

## Overview
Valheim, the PC survival game based on Norse mythology, can be intensive to run if your world contains heavy terrain modifications or building structures.  Since the game presently lacks any good or consistent way to benchmark frames per second (FPS) performance for such worlds, this project serves as a rudimentary world file containing building structures of increasing design complexity by which frames per second can be measured and compared.

## How to Install
Copy the `Benchmark.db` and `Benchmark.fwl` world files from this repository into your Valheim `worlds` directory, usually located in Windows user directory `C:\Users\<YOUR_USER_NAME_HERE>\AppData\LocalLow\IronGate\Valheim\worlds`.  You can use the directory alias `%UserProfile` in your path address if you prefer: `%UserProfile%\AppData\LocalLow\IronGate\Valheim\worlds`

## How to Use
1. Install the benchmark world files, per the section above
2. Run Valheim on the computer and configuration you wish to benchmark
3. Start a new game, loading the world `Benchmark`
4. Upon visiting the benchmark world, you'll see four portals, labeled `Test 1`, `Test 2`, `Test 3`, and `Test 4`.  These portals lead to regions which each contain a building structure whose complexity (number of pieces) increases exponentially in relation to the test number.
5. Visit each test structure, and face it so that the whole structure is in view as much as possible.
6. Press F2 to show a diagnostic dialog that includes information such as frames per second (FPS)
7. Use the FPS numbers to compare how well your computer and configuration perform under regions of increasing complexity
