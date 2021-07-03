#include<bits/stdc++.h>

#include<windows.h>

#include<conio.h>

#include<time.h>

#include<string>
using namespace std;
typedef struct Frame
COORD position[2];
int flag;
  SetPos(31, 12)
cout<<"得　　分："<<score;
SetPos(31, 13);
cout<<"获得称号："<<title;
Sleep(1000);
cout<<"继续？ 是（y）| 否（n）制作：最牛的嘻嘻嘻";
bulletMove();
drawBulletToNull();
rawBullet();
judgeEnemy();
flag_bullet++;
if( 5 == flag_bullet )
flag_bullet = 0;
void Game::Pause()
SetPos(61,2);
cout<<"               ";
SetPos(61,2);
cout<<"暂停中...";
char c=_getch();
while(c!='p')
c=_getch();
SetPos(61,2);
cout<<"         ";
judgePlane();
else if ('p' == x)
Pause();
Shoot();
else if( 'e' == x)
//CloseHandle(MFUN);
GameOver();
/* 处理子弹 */
if( 0 == flag_bullet )
