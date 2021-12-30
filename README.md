# portaudio GO/C implementation

This package provides an interface to the [PortAudio](http://www.portaudio.com/) audio I/O library.  

To build this package you must first have the PortAudio development headers and libraries installed.  

### Port Audio Installation
  - MAC
  brew install portaudio

  - WINDOWS
  Instructions using [MAKE](http://www.portaudio.com/docs/v19-doxydocs/compile_cmake.html)

  - POSIX
  `apt-get install portaudio19-dev`

Some systems provide a package for this; e.g., on Ubuntu you would want to run .  On other systems you might have to install from source.



## Special Thanks
Thanks to [Gordon Klaus](http://godoc.org/github.com/gordonklaus/portaudio) for original repo development

Thanks to sqweek for motivating and contributing to host API and device enumeration.
