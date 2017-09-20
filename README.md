# PowerSpec-Ultra-Proxy

Disclaimer: THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) 
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. PLEASE NOTE THAT THIS SOFTWARE IS THEORETICALLY CAPABLE OF FLASHING AN IMPROPER FIRMWARE TO YOUR PRINTER, DO NOT ATTEMPT TO UPDATE YOUR PRINTERS FIRMWARE WHILE USING THIS SOFTWARE.
 

This is a simple proxy program that is designed to allow the users of the PowerSpec Ultra to print with flashprint over Wifi.  Please note that this is an early testing version and it is very slow at the moment.

USAGE: python printerProxy.py [Local IP] [Local Port] [Remote IP] [Remote Port] [Send First (bool)]
EXAMPLE: python printerProxy.py 127.0.0.1 9000 10.12.132.1 9000 True

This script is designed to run with python 2, it is possible to port it to python 3 however I have not found the need.

NOTE: This script is heavily based on a script provided in the book Black Hat Python by Justin Seitz ( ISBN-13: 978-1-59327-590-7 )

NOTE: All information about the FlashForge Dreamer used in this script was taken from the offical user guide (page 40).
http://www.flashforge-usa.com/assets/manual/flashforge_dreamer_user_guide_v2_0_2.pdf?cd6e8a
