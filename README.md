# NimiqMessage

Just like mini notice-board.<br>


## How to write your messages on Nimiq blockchain?<br> 

Open your Nimiq wallet https://safe.nimiq.com ,<br> 

Send NIM(>=0.00001 NIM) and write transaction_message(=<64 chars) <br>

to **NQ07 0000 0000 0000 0000 0000 0000 0000 0000** <br><br>



## How to read all of your messages?<br>
*todo: If you want to dev the client, commit to here*<br>
http://oyjc.com/nimiq/message/adr/{your_nimiq_address}<br>

http://oyjc.com/nimiq/message/adr/{your_nimiq_address}?sort=up<br><br>



## How to read all of peoples messages?<br>

http://oyjc.com/nimiq/message<br><br>


## How to write/view more content in one post?<br> 

You need to split your content into multiple transaction_messages, <br>

send the second and subsequent content must starting with **+**, and your content will follow.<br>


Example: <br>

"Assume I'm more than 64 bytes.... blablabla...endof64. The second text is here blabla"<br>

1, first transaction_message: Assume I'm more than 64 bytes.... blablabla...endof64.<br>

2, second transaction_msessage:  +The second text is here blabla<br><br>

## Usecase <br>
Usecase 1: after the newbie get 1 NIM from faucet, can post on notice-board via use NIM.<br>
Usecase 2: some bots can post logs, the logs can't be change.<br>

