# Lines95
Line up 5 balls (or more) to remove them, and try achieving the highest score before you cannot move. The original source code for this game was created by Anatoly Podgoretsky. Since he shared it "as is with no liability" (see original licence below), I share it here under a MIT license. I stripped down the source code to purely the game part. Compiles in Turbo Delphi.

Original source: https://torry.net/pages.php?id=352#1805

Angus Johnson released a much more polished version here, including high scores, sounds on/off and 3 sets of improved graphics:
http://www.angusj.com/lines95/
However, he didn't release the source code, hence why I try to fill this gap with this repository. If you want to disable/enable sound, just create a menu item with this code:
  JumpSnd := not JumpSnd;
  RemoveBallSnd := not RemoveBallSnd;
  BadMoveSnd := not BadMoveSnd;

-----------------
Legal Information
-----------------

THIS SOFTWARE IS PROVIDED TO THE USER "AS IS."
ANATOLY PODGORETSKY MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED,
WITH RESPECT TO THIS SOFTWARE AND/OR ASSOCIATED MATERIALS PROVIDED TO
THE USER, INCLUDING BUT NOT LIMITED TO ANY WARRANTY OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE OR AGAINST INFRINGEMENT.
ANATOLY PODGORETSKY DOES NOT WARRANT THAT THE FUNCTIONS
CONTAINED IN THE SOFTWARE WILL MEET YOUR REQUIREMENTS, OR THAT THE
OPERATION OF THE SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE, OR THAT
DEFECTS IN THE SOFTWARE WILL BE CORRECTED.
FURTHERMORE, ANATOLY PODGORETSKY DOES NOT WARRANT OR MAKE ANY REPRESENTATIONS
REGARDING THE USE OR THE RESULTS OF THE USE OF THE SOFTWARE OR ANY
DOCUMENTATION PROVIDED HEREWITH IN TERMS OF THEIR CORRECTNESS, ACCURACY,
RELIABILITY, OR OTHERWISE.  NO ORAL OR WRITTEN INFORMATION OR ADVICE
GIVEN BY ANATOLY PODGORETSKY SHALL CREATE A WARRANTY OR IN ANY WAY
INCREASE THE SCOPE OF THIS WARRANTY.

LIMITATION OF LIABILITY -- ANATOLY PODGORETSKY IS NOT LIABLE FOR ANY
CLAIMS OR DAMAGES WHATSOEVER, INCLUDING PROPERTY DAMAGE, PERSONAL INJURY,
INTELLECTUAL PROPERTY INFRINGEMENT, LOSS OF PROFITS, OR INTERRUPTION OF
BUSINESS, OR FOR ANY SPECIAL, CONSEQUENTIAL OR INCIDENTAL DAMAGES, HOWEVER
CAUSED, WHETHER ARISING OUT OF BREACH OF WARRANTY, CONTRACT, TORT
(INCLUDING NEGLIGENCE), STRICT LIABILITY, OR OTHERWISE.
