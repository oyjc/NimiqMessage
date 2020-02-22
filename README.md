# NimiqMessage

Just like mini notice-board.<br>


## How to write your messages on Nimiq blockchain?<br> 

Open your Nimiq wallet,<br> 

Send NIM(>=0.00001 NIM) and write transaction_message(=<64 chars) <br>

to **NQ07 0000 0000 0000 0000 0000 0000 0000 0000** <br><br>



## How to read all of your messages?<br>

http://oyjc.com/nimiq/message?{your_nimiq_address}<br>

http://oyjc.com/nimiq/message?{your_nimiq_address}&sort=up<br><br>


## How to read all of peoples messages?<br>

http://oyjc.com/nimiq/message<br><br>


## How to write/view more content in one post?<br> 

You need to split your content into multiple transaction_messages, <br>

send the second and subsequent content must starting with **+**, and your content will follow.<br>


Example: <br>

"Assume I'm more than 64 bytes.... blablabla...endof64. The second text is here blabla"<br>

1, first transaction_message: Assume I'm more than 64 bytes.... blablabla...endof64.<br>

2, second transaction_msessage:  +The second text is here blabla<br>

