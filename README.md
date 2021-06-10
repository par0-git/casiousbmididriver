# Casio USB MIDI Driver for macOS

## New information
If you are NOT on an M1 Mac / can use the original driver, use that instead!! This is not great and it's a lot easier to use the installer.

But if you can't use the original, heres some information before you proceed:
casiousbmididriver is made by francoisferland, I have just created a (pretty-bad!) Xcode project for the 10.7 version that can be compiled on & for newer Macs. The Xcode project is based on the one provided with the original sample code by Apple. It'll build to a random location in the Xcode application and you can just get the plugin that comes out and put it in /Library/Audio/MIDI Drivers.

## Original
This is the new home of the MIDI Driver for older, USB-only Casio keyboards that do not work out of the box on Mac OS X. The driver is entirely based on sample code from Apple's SDK, and should work with many models of Casio keyboards. The project originated on Google Code, and you can still visit its old home at:

http://code.google.com/p/casiousbmididriver

## Installation

The latest release supports Intel Macs on Mac OS X 10.7 (Lion) and up (? might be broken on higher versions I can't confirm):

https://github.com/francoisferland/casiousbmididriver/releases/download/release-1.0/Casio.USB.MIDI.Driver.10.7.pkg

To install the driver, simply double-click on the installation package. It will install for all users on your machine.

You should then be able to plug your keyboard with a USB cable and power it up, it will show up in the Audio & MIDI Setup utility as "Casio USB Keyboard".

**IMPORTANT NOTICE** THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
