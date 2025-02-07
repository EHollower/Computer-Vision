Biblioteci necesare

python==3.13.0 (tags/v3.13.0:60403a5, Oct  7 2024, 09:38:07) [MSC v.1941 64 bit (AMD64)]
opencv_python==4.10.0
numpy==2.1.2
matplotlib==3.9.2

Codul este scris in Jupiter Notebook impreuna cu Visual Studio Code
Pathurile fisierelor sunt relative la fisierul unde se afla soltuia
Pentru ca soltuia sa ruleze testele este necesar modficiare variabilei `folder_path_input` din sectiunea Evaluare
Se pot modifica de asemnea parametrii pentru numarul de jocuri si numarul de mutari facute in aceeasi sectiune

Task1, este necesar accesul la folderul imagini_auxiliare preferabil cele de antrenare
Task2 are dedicata o sectiune unde se extrag date, functiile nu vor mai fi apelate setul de date final se află in folderul solutie/cifre

Pentru a obtine output-ul final (Task 1. 2. si 3.) se va rula fiecare celula a solutiei care se afla in: /solutie/solutie.ipynb

## About project

The project is composed of detecting moves made on the board of a game of [Mathable](https://boardgamegeek.com/boardgame/2858/mathable).

We needed to compute the position on which moves where made, compute the digits on the respective piece on the respective move and finally compute the score for two players.