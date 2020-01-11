# wiz
```
simple map walk macro.
```
```
/*command help
!TITLE@black#xyz
こまち「泉の水を飲みますか？」

>>>#TITLE
$ memory
# is board
! is sound
!! is sound effect
@ is background
@@ is character picture
WAI:select wait
WAI 300:active wait
*/

#loading //config
!
!!
@
@@
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

//
「OBJECT OK...」
WAI 200
WAI
>>> #CLEAR
>>> #TITLE

#CLEAR
!
!!
@
@@
「」
「「」」
CUR ＊
>>>

//entrypoint
#TITLE

#other...

```
