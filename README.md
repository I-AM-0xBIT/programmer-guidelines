# Programmer Guidelines

### This is my take on how to code

## Setup

#### For me setup is extremely important and it includes the right IDE to the fonts we use (I'll explain why later).

#### IDE

* I've been using Jetbrains IDE's as my primary coding environment but since most of them are paid unless I'm working in my office I don't have access to it. In times like these I prefer using VSCode but it's Intellisense isn't that good as what Jetbrains IDE's offer.

#### Theme

* I prefer using Material theme for all my IDE's as it's visually appealing and gives me a sense of coding in the same environment irrespective of the IDE.

#### Fonts

* Well there are many fonts that people prefer like firacode but for me it's going to be Jetbrains mono since it comes with font ligatures and is visually more appealing.

#### Comments Color (Prefer for Material theme as it doesn't come with different colors for different types of comments)

##### I'll explain later on why i prefer these choices

* Block comments - HEX value - #93B9C3
* KDoc comments - HEX value - #3DDC84
* Line comments - HEX value - #616161

## Coding Style

#### I'll be using quite a few examples from [Jupeter's clean code](https://github.com/jupeter/clean-code-php)

#### No more than 2 Parameters

* Less parameters are always favoured when creating a function. 
* If multiple values are to be passed depending on the language or framework choose a proper object to pass it.
* Eg - Using bundle to pass data in Android
