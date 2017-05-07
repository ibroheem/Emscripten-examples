# Emscripten
Emscripten is an LLVM-based project that compiles C and C++ into highly-optimizable JavaScript in asm.js format. This lets you run C and C++ on the web at *near-native (there is a lot of problem with this  word)* speed, without plugins. 

### Quick Guide:
[From: http://kripken.github.io/emscripten-site/docs/getting_started/downloads.html]  
** Installation (Linux): 

<pre>

<b>Setup build environment for Debian & derivatives, do siimilar for your distro</b><br/>
#Update the package lists
sudo apt-get update

# Install *gcc* (and related dependencies)
sudo apt-get install build-essential

# Install cmake
sudo apt-get install cmake

<b>Emscripten Installation </b><br/>
wget https://s3.amazonaws.com/mozilla-games/emscripten/releases/emsdk-portable.tar.gz
# Fetch the latest registry of available tools.
./emsdk update

# Download and install the latest SDK tools.
./emsdk install latest

# Make the "latest" SDK "active"
./emsdk activate latest

# Set the current Emscripten path on Linux/Mac OS X
source ./emsdk_env.sh

</pre>
