# PROJECT TITLE: **ONLINE AUCTION AND BIDDING SYSTEM**

**TEAM NO:** KLH/PSPJ/S14/T6

**TEAM MEMBERS:**

1. **2620080072** - Madhu Priya
2. **2620030223** - Tanshika Sai

**SUPERVISOR:** Dr. Madhavi Karamudi

---

## Abstract

The **Online Auction & Bidding System** is a console-based Java application designed to simulate the complete process of an online auction. The system allows multiple bidders to participate in auctions, place bids, and compete for different auction lots. It validates bids based on the current highest bid, minimum bidding increment, and auction status. The system also supports **proxy bidding**, allowing bidders to specify a maximum amount they are willing to pay while automatically increasing their bids when necessary. Auctions can be closed based on their specified closing time, after which the system determines the winning bidder and final selling price. It also identifies unsold items and generates settlement and sales reports. The project is developed progressively alongside the Java syllabus, incorporating concepts such as conditions, loops, methods, arrays, object-oriented programming, interfaces, exceptions, records, file handling, collections, and streams. This approach demonstrates the practical application of Java concepts in developing a structured and functional auction management system.


---

## PROJECT STRUCTURE

```text
Online-Auction-Bidding-System/
│
├── src/
│   ├── Main.java
│   ├── AuctionHouse.java
│   ├── Lot.java
│   ├── Bidder.java
│   ├── Bid.java
│   ├── BidValidator.java
│   ├── DefaultBidValidator.java
│   ├── AuctionException.java
│   └── Reportable.java
│
├── README.md
├── data/
└── reports/
```

---

## EXECUTION INSTRUCTIONS

1. Open the `.java` file in Notepad and save it with the `.java` extension.
2. Open Command Prompt, navigate to the project folder, and compile using `javac Main.java`.
3. Run the program using `java Main` and follow the instructions displayed in the console.

---

## GIT COMMANDS

```bash
git init
git add .
git commit -m "Initial project setup"
git branch -M main
git remote add origin <repository-url>
git push -u origin main
```

### For future updates

```bash
git add .
git commit -m "Updated auction system"
git push
```


   

