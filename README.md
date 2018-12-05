# BlackjackGameAppClient
Blackjack game that uses the Blackjack web service.

# Description
The blackjack application keeps track of the player's and dealer's cards and the web service tracks the cards that have been dealt.

# Getting Started
## Prerequisites
- JDK 1.8
- [Blackjack web service](https://github.com/lnpeng/BlackjackService)

## Installing
- Creating a local repository.
```
git clone git@github.com:lnpeng/BlackjackGameAppClient.git
cd BlackjackGameAppClient
```

- Adding the Blackjack web service reference.
  - Right click the project name in the NetBeans **Projects** tab and select **New > Web Service Client…** from the pop-up menu to display the **New Web Service Client** dialog.
  - In the WSDL URL field, specify the URL http://localhost:8080/Blackjack1/BlackjackService?WSDL
  - Click **Finish** to create the web service reference

## Running the tests
### Test the Blackjack client
- Launch the Blackjack client.
- ![Test](https://github.com/lnpeng/BlackjackGameAppClient/blob/master/Screen%20Shot%202018-12-04%20at%205.26.41%20PM.png)

# Build
* [Ant](https://ant.apache.org/) - Automating software build process.
