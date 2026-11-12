🇧🇷 [Leia em português](README.pt-BR.md)

# Java Coding Exercises

I finished the beginner-to-intermediate module of the Java10x course, taught by Horácio Fiasco, with an uncomfortable feeling. I understood every lesson. I followed the code, agreed with the explanations, took notes on everything. And I still wasn't sure I could open a blank file and solve a problem on my own.

Watching someone solve a problem is not the same as solving one. Think of reading about how to ride a bike: you come away knowing the names of the parts and still fall in the first few feet.

This repository is my attempt to stop falling. Ten challenges, from a bare-bones console app to a university library system, all in plain Java. No framework, no external libraries.

## How it works

The problem statements say **what** has to happen, never **how**. None of them tells me to create an abstract class or use a stack. Making that call is the exercise. Some constraints nudge the solution in a direction (in Tic-Tac-Toe, for instance, I'm not allowed to hand-write the eight winning combinations, and the temptation is real), but the final decision is always mine.

There are no ready-made solutions. When I get stuck, I ask for a hint, and the hints go from subtle to direct. I only look at a full solution if I explicitly ask for one, and the goal is to ask as rarely as possible.

The exercises were designed with the help of Claude (Anthropic), based on the list of topics from the module. It also reviews my solutions: what's right, what's wrong and why, without rewriting my code. The code in every solution is mine.

## The three levels

**Level 1: Consolidation (exercises 1 to 4).** Fundamentals, combined. Menus, loops, arrays, matrices and the first classes, with the added demand that the code stay organized.

**Level 2: Integrated application (exercises 5 to 7).** The problem stops fitting inside a single class. Hierarchies, interfaces, enums, generics and records come in for real, and the question changes from "how do I make this work?" to "how do I structure this so it survives change?"

**Level 3: Complex challenges (exercises 8 to 10).** Data structures chosen and justified, relationships between many objects, and a final project that pulls the whole module together.

Difficulty here doesn't come from writing more code. It comes from having more decisions to make.

## Progress

| # | Challenge | Level | Status |
|---|-----------|-------|--------|
| 1 | ATM Terminal | 1 | ⬜ |
| 2 | Class Grade Analyzer | 1 | ⬜ |
| 3 | Console Tic-Tac-Toe | 1 | ⬜ |
| 4 | Corner Store Inventory | 1 | ⬜ |
| 5 | Vehicle Rental Company | 2 | ⬜ |
| 6 | Online Store Checkout | 2 | ⬜ |
| 7 | Movie and Series Catalog | 2 | ⬜ |
| 8 | Text Editor with Undo and Redo | 3 | ⬜ |
| 9 | Clinic Service Desk | 3 | ⬜ |
| 10 | University Library | 3 | ⬜ |

Each finished exercise gets its own folder with the problem statement, my solution and the review notes.

## What's being practiced

Primitive and reference types, conditionals, loops, `Scanner`, `switch`, the ternary operator, arrays and matrices. Then classes, objects, constructors and overloading, encapsulation, inheritance, abstract classes, interfaces, polymorphism, `final`, enums, generics, records and the collections `List`, `ArrayList`, `LinkedList`, `Stack` and `Queue`.

Every one of these topics shows up in at least one challenge, and none of them shows up alone.

## Running the code

You'll need Java 16 or higher (because of records). Instructions for each exercise live in the README inside its own folder.

## A caveat

I don't know if ten exercises are enough to consolidate a whole module. Probably not. But I'd rather have ten problems where I got it wrong, understood why and redid it than a full course of lessons watched without writing a single line.