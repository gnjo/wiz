# wiz
```
simple map walk macro.
```
```
/*command help
#TITLE
@black
!walksong
こまち「泉の水を飲みますか？」

>>>#TITLE
$ memory
# is board
@ board image
! is sound
!! is sound effect
@ is board image
@@ is character
WAI:select wait
WAI 300:active wait
WAI [a]:wait the key a
「通常メッセージ」
「「キーヘルプメセージ」」
「「「上部情報、基本使わない」」」
*/

#loading //config
>>> #CLEAR
「KEY LOADING...」
[x]
[y]
[a]
[b]
[l]
[r] 
[^] //up arrow
[v] //down arrow
[<] //left arrow
[>] //right arrow
CUR ＊
//
「KEY OK...」
「OBJECT LOADING...」
//
@black FFFFFF
@white 000000
//
「OBJECT OK...」
WAI 200
WAI
>>> #CLEAR
>>> #TITLE

#CLEAR //clear board
!
!!
@
@@
「」
「「」」
「「「」」」
CUR ＊
FON FFFFFF
>>>

//entrypoint
#TITLE

#other...

```
