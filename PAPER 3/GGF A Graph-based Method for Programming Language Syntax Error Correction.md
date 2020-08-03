# <u>GGF: A Graph-based Method for Programming Language Syntax Error Correction:</u>

## AUTHORS:

​		This paper was written by *Liwei Wu, Fei Li, Youhua Wu and Tao Zheng.*

## VENUE:

​		*At Beakje, Goguryeo, Silla and Tamna of Korean Kingdoms.*

## DATE:

​		*Wed 15 Jul 2020* at ICPC-Session 11.

[Video Link](https://youtu.be/O53YnbJ4REc "a new site")

## ABSTRACT:

​		*In programming Language, a Syntax error is an error in  the syntax of a sequence of characters that is intended to be written in compile-time.* A program will not compile until all Syntax errors are corrected. For interpreted languages.

​		However, a Syntax error may be detected during program execution, and an interpreter's error message might not differentiate Syntax errors from errors of others kinds.

​		A Syntax error may also occur when an invalid equation is entered into a calculator. This can be caused for instance, by opening brackets without closing them, or less commonly, entering several decimal points in one number. A compiler will flag a syntax error when given source code that doesn't  meet the requirements of the language grammar. 

​		<u>In this paper, we propose a novel deep supervised learning model, called Graph-based Grammar Fix (GGF), to help programmers, locate and fix the Syntax errors. GGF, treats the code as a mixture of the sequence and graphs.</u>

​		The graph build upon the abstract Syntax tree(AST) Structure information. GGF encodes an erroneous code with its sub-AST structure predict, the error position using pointer network and generates right token. GGF is trained with the correct programs from the Deep fix dataset with intentionally injected Syntax errors. 

​		Error Correction is the process of detecting errors is transmitted messages and reconstructing the original errors-free data-error correction ensures that corrected and error-free messages are obtained at receiver side.

##### *Some major types of Error Correction.*

* Automatic repeat request(ARQ)
	
* Forward error Correction
	
* Hybrid Schemes
	
* Minimum distance coding
	
* Repetition codes
	
* Parity bit

* Checksum

* Cyclic redundancy check

  ​		System Capable of requesting the retransmission of bad messages in response to error detection include an automatic request for retransmission, or automatic repeat request (ARQ) processing, in their communication software package, they use acknowledgement messages and timeouts to achieve better data transmission.

  ​		ARQ is an error Control (error Correction) method that uses error-detection codes and positive and negative acknowledgement or a timeout happens before acknowledgment is received the ARQ makes the transmitter resend the message.

  ​		*Error-Correcting Code (ECC) or Forward Error Correction (FEC) is a method that involves adding parity data bits to message.* These parity bits will be read by the receiver to determine whether an error happened during transmission or storage.

  ​		In this case, the receiver Checks and Corrects errors when they occur. It doesn't ask the transmitter to resend the frame or message.

  ​		A Hybrid method that combines both ARQ  and FEC functionality is also used for error correction. In this Case, the receiver ask for retransmission only if the parity data bits are not enough for successful error Detection and Correction.

