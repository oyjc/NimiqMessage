# NimiqMessage

Just like mini notice-board.


How to write your messages on nimiq blockchain?
Open your Nimiq wallet, 
Send NIM(>=0.00001 NIM) and write transaction_message(=<64 chars) 
to NQ07 0000 0000 0000 0000 0000 0000 0000 0000 

How to read all of your messages?
http://oyjc.com/nimiq/message?{your_nimiq_address}

How to read all of peoples messages?
http://oyjc.com/nimiq/message

How to write more transaction_message?
You need to split your message into multiple messages, 
send the second and subsequent messages must starting with +, and your message will follow.
Example: 
"Assume I'm more than 64 bytes.... blablabla...endof64. The second text is here blabla"
1,first tx_message: Assume I'm more than 64 bytes.... blablabla...endof64.
2,second tx_msessage:  +The second text is here blabla
