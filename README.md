# spim-grader
Quick python script to grade MIPS homework submissions

Uploading this mainly to make sharing slightly easier.

Uses python's subprocesses library to spawn processes to test MIPS programs using spim's command-line option. Returns results based on success/syntax error/invalid address error/hanging (pretty sure that's all there is).
Runs all sample test files in /samples against all submitted homeworks in /submissions. Stores output in /results.
/samples and /submissions must exist for script to run.
See [/samples/.example](/samples/.example) and [/submissions/.example](/submissions/.example) for instructions on specific input.

Prerequisites: python 2.7 and cli spim (apt-get spim)

NOTE: I've tested this on linux (MINT Rafaela x64) but it might be wonky on windows because of its use of command-line spim and threading. YMMV
