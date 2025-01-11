# Elixir Enum.each and Process.exit Unexpected Termination

This repository demonstrates a potential issue when using `Enum.each` in Elixir and prematurely exiting a process within the anonymous function.  The example shows how `Process.exit` within the `Enum.each` loop causes the iteration to stop unexpectedly.  A solution is provided to handle this situation more robustly.