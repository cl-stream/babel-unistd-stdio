# unistd-stdio

Standard I/O library for cl-stream using cffi-unistd as a backend.

Depends on :
- https://github.com/cl-stream/cl-stream
- https://github.com/cl-stream/unistd-stream

## Function: stdin => *unistd-input-stream*
Returns an existing UNISTD-INPUT-STREAM or creates one reading from
UNISTD:+STDIN-FILENO+.

## Function: stdout => *unistd-output-stream*
Returns an existing UNISTD-OUTPUT-STREAM or creates one writing to
UNISTD:+STDOUT-FILENO+.

## Function: stderr => *unistd-output-stream*
Returns an existing UNISTD-OUTPUT-STREAM or creates one writing to
UNISTD:+STDERR-FILENO+.
