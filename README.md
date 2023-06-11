# Ballot-Voting-using-Blockchain
Here, since i have used Byte32 instead of String, you need to create two node js files, to encode and decode the bytes32 and string names.
There, create two files, namely createBytes.js and parseByte.js as it is there in the transform folder.
open https://remix.ethereum.org/ , create a file(i have named ballot-vot.sol here) and there will be 10 accounts by default in the account section
inside run and deploy transaction. set the environment to Remix VM, give the candidate names in bytes32 format using the node files and give it inside ["","",....]
the double quotes, next to the deploy option after that,
let the first account be chairperson, to make all the other accounts, right to vote,
copy the next account's address, and paste it on "giverightstovote" and make sure you make the current account as chairperson,
do the same process for all the other accounts,
Now, all accounts are eligible to vote,
Now, choose one account, next to vote, give index such that, 1st candidate will have index 0, 2nd candidate will have 1, and so on.
now click candidatewinner to see the index no of the winner, and candidatename to see the winner's name in bytes32 format, parse it to string, to see their name in 
english language
For more clear understanding, watch this video : https://drive.google.com/drive/folders/1X2_Uc8S1clKge8QlYnAtlDsNr2_RWexf
