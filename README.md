<div align="center">

## computalk


</div>

### Description

Make your computer talk
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Andrew Bright](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/andrew-bright.md)
**Level**          |Beginner
**User Rating**    |2.0 (20 globes from 10 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Algorithms](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/algorithms__3-29.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/andrew-bright-computalk__3-310/archive/master.zip)





### Source Code

```
#include <iostream.h>
#include <conio.h>
#include <stdio.h>
#include <bios.h>
main()
{
	clrscr();
	int choice;
	int choice2;
	int choice3;
	char FirstName [20];
	cout << "Hi this is your computer talking\n What is your name" << endl;
	cin >> FirstName;
	clrscr();
			cout << "Hello " << FirstName << " what would you like to do now" << endl;
			cout << "\nMenu\n\n 1)EXIT \n 2) Keep talking to me" << endl;
			cin >> choice;
			switch ( choice ) {
				case 1:
				clrscr();
				cout << " ok bye " << FirstName << " talk to you later" << endl;
				cout << "Press Alt + F4 to continue to windows" << endl;
				break;
				case 2:
				clrscr();
				cout << "what would you like to talk about?" << endl;
				cout << "\nMENU\n\n 1) Talk about me \n 2) Talk about you" << endl;
									}
					cin >> choice2;
					switch ( choice2 ) {
					case 1:
					unsigned memory_size;
					memory_size = _bios_memsize();
					printf("RAM size = %dk\n", memory_size);
					break;
					case 2:
					clrscr();
					cout << "ok, if you had the oppertinity to do one thing from this list\n what would you do?" << endl;
					cout << "\nMENU\n\n 1)Go to bed\n 2)Watch TV\n 3)Go to the cinema\n 4)Have flying lessons\n 5)Go on holiday\n 6)Other" << endl;
					cin >> choice3;
					switch (choice3) {
					case 1:
					cout << "That shows that you are lazey " << FirstName << endl;
					break;
					case 2:
					cout << "That shows that you do not get out enough " << FirstName << endl;
					break;
					case 3:
					cout << "That shows that you have a good social life " << FirstName << endl;
					break;
					case 4:
					cout << "That shows that you have a good sence of adventure " << FirstName << endl;
					break;
					case 5:
					cout << "That shows that you have a lot of charictor " << FirstName << endl;
					break;
					case 6:
					cout << "ok" << endl;
					break;
										 }
					break;
					return 0;
											 }
}
```

