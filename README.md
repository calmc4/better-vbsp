# better-vbsp
Better-VBSP is an improved BSP source compiler for the Source Engine, allowing the compilation of larger and more complex maps.

Despite these improvements and increased limits, VBSP remains unupdated for Source games and is often not fully utilized, as it enforces safe ranges to maintain compatibility with most games.

This version removes some hard-coded limitations that trigger various error messages (e.g., num_brushes, vertexes, too many brushes in one leaf).

It is now more likely that your map will crash in the engine rather than fail to compile.

It has worked fine in all cases for me, successfully compiling two large maps that previously failed due to the aforementioned errors.

VVIS and VRAD are 100% untouched.

All that should be needed is to replace your vbsp.exe (located within your bin folder of your respective game directory) with this version and it should now be able to compile all maps in any compiler (hammer, hammer++, source sdk, compile pal, etc.)

This was all done using hex editing with the HxD and Ghidra software.
