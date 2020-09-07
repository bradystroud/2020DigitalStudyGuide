# Topic 1: Digital methods for exchanging data

<i>Written by Brook Jeynes and Brady Stroud</i>

# Encryption

* <i>Criteria: 
	* Recognise and describe encryption and authentication strategies appropriate for securing data transmissions and their differences
    	* features of symmetric (Data Encryption Standard — DES, Triple DES, AES — Advanced Encryption Standard, Blowfish and Twofish) and assymetric (RSA) encryption algorithms
    	* How data compression, encryption and hashing are used in the storage and transfer of data
  
	* Symbolise, Analyse and Evaluate
    	* Caesar, Polyalphabetic (e.g. Vigenere and Gronsfield), and one-time pad encryption algorithms</i>

- - -
<br>

**Encryption**

Encryption is the process of scrambling data so that only the desired party can understand that information. In more technical terms it is the process of converting plain text to cipher text.


  ```
  "Hello"  --->  [encryption]  --->  "SNifgNi+uk0="
  plaintext                          ciphertext
  ```



**Compression**

Compression is the process used to reduce the storage space a file or program uses, this allowing more files to fit into the same amount of space. This process is especially useful when transferring files over the internet due to larger files taking a longer time to transfer.

**Hashing**
Hashing is the process in which an input is turned into a fixed sized value. Hashing, unlike encryption, has an output that cannot be reversed to form the key. This means that if a hacker gained access to the hashed database they could only gain access to the keys, which cant be reversed to gain the passwords. However, someone with the password can hash theirs and check it against the stored hash to gain access.

- - -

In modern time there are two main types of Cryptography algorithms used to protect our data over transfer, symmetric and asymmetric key encryption. <br>

**Symmetric Key Encryption**

Symmetric key encryption, also known as a symmetric algorithm, is a type of encryption that uses one key to encrypt and decrypt data, a secret key, a public key and a private key. <i>"Keys are random bits that are used by the algorithm to transform the material into its encoded format and back to plain text." - ("Encryption 101", 2020)</i>. Some advantages to using symmetric key encryption include its encryption speed and efficiency for large projects with disadvantages consisting of its need to keep the secret key, this can become tricky when dealing with multiple locations. <br>

* **Symmetric Key Ciphers**	
	
	<ol>- DES: A 64 bit block cipher that uses a 56-bit key.</ol>
	<ol>- Triple DES (3DES): Uses three separate 56 bit encryption keys. The message is encrypted using one key, encrypted again using a second key and further encrypted by using either a first or third key.</ol>
	<ol>- AES: A variant of [the] Rijndael [block cipher], with a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits. - ("Advanced Encryption Standard", 2020)</ol>
	<ol>- Twofish: A symmetric block cipher which operates on 128 bit blocks and employs 16 rounds with key lengths up to 256 bits.</ol>
<ol>- Blowfish: A symmetric block cipher which operates on 64 bit blocks and employs 16 rounds with key lengths up to 448 bits and uses large key-dependant S-boxes [S-box: "<i>a basic component of symmetric key algorithms which performs substitution"</i> - ("S-box", 2020)].</ol>
	</li> <br>

**Asymmetric Key Encryption**

Asymmetric key encryption, also known as an asymmetric algorithm, is a type of encryption that uses two separate keys, with one being used to encrypt and the other to decrypt data. The key pair being referenced as a public key and private key. The public key is used to send the message and the private key being the one to decrypt said message. Some advantages to using asymmetric key encryption include its encryption extended functionality and its scalability for larger projects with its main disadvantage being the speed of the algorithm. <br>

* **Asymmetric Key Ciphers**
	<ol>- RSA: <i>"In RSA, the public key is generated by multiplying two large prime numbers p and q together, and the private key is generated through a different process involving p and q. A user can then distribute his public key pq, and anyone wishing to send the user a message would encrypt their message using the public key... When the user receives the encrypted message, they decrypt it using the private key and can read the original text."</i> - (Katz et al., 2020)</ol>
</li> <br>
	
---

**Caesar Cipher**
	
The Caesar Cipher is one of the earliest known ciphers to have been invented, it is known as a substitution cipher. It works in such a way where each letter in the message is shifted a certain number of places down the alphabet. For example, for a shift of 1 character:
	
```
  "Hello"  --->  [encryption]  --->  "Ifmmp"
  plaintext                          ciphertext
```

<br>

**Polyalphabetic**

A polyalphabetic cipher was the first main solution at a problem that had plagued ciphers for a while, frequency analysis. Not all characters in the alphabet are made equally and its because of this people were able to start analysing encrypted text looking for which characters appeared the most. This allowed them to map ciphered characters to uncyphered characters based on their frequency rating. An example of this is that the character "e" is the most common character in English so <i>"if 'e' has been encrypted to 'X', then every 'X' was an 'e'. Hence, the most common letter in the ciphertext should be 'X'." - (Rodriguez-Clark, 2020)</i>

Polyalphabetic ciphers incorporates multiple ciphers in one so a single plain text character will not always be the same cipher character. 

```
Monoalphabetic
  "Hello"  --->  [encryption]  --->  "Ifmmp"
  plaintext                          ciphertext

Polyalphabetic
  "Hello"  --->  [encryption]  --->  "Ifgmp"
  plaintext                          ciphertext  
```

 <br>

**Polyalphabetic Ciphers**	

<ol>- Vigenere: "The Vigenère cipher is a method of encrypting alphabetic text by using a series of interwoven Caesar ciphers, based on the letters of a keyword." - ("Vigenère cipher", 2020)</ol>
<ol>- Gronsfield: "The Gronsfeld cipher is essentially a Vigenere cipher, but uses numbers instead of letters. So, a Gronsfield key of 0123 is the same as a Vigenere key of ABCD." - ("Gronsfeld Cipher", 2020)</ol>

</li> <br>

**One-time Pad Encryption Algorithms**



- - -

## Visual Communication

* <i>Criteria: 
  * How usability principles are used to inform solution development
  * How the elements and principles of visual communication inform user interface development</i>

- - -

<br>

**Usability Principles** <br>
There are seven main usability principles that will be focused on, hierarchy, harmony, contrast, repetition, alignment, proximity and balance. The combination of these principles help the users navigate though a webpage with ease giving them the best experience and allowing them to know how the webpage is meant to be used. These principles help visually and practically for the user with the use of colour design all the way to easy navigation for the blind (using screen readers). There are also usability elements, space, line, colour, shape, texture, tone, form, proportion and scale which aid the usability principles. <br>

* **Usability Principles**
	<ol>
		- Hierachy: "This principle can be used to highlight the importance of particular content and features, encouraging users to respond to important elements. When designing a web page, it can be helpful to keep in mind the natural tendency of users to assign greater importance to content at the top left of the screen, and less importance as they move from the top down and from left to right." - (School Resources, 2020)</ol>
	<ol>
		- Harmony: "Harmony offers an interpretation of proximity to ensure components as a whole provide valuable meaning and are complementary across the interface. In a data driven context, it is not always harmonious to place certain datasets with others. Sometimes it is better to place datasets on separate screens to avoid confusion or otherwise improve the experience." - (School Resources, 2020)</ol>
	<ol>
		- Contrast: "Contrast is what you see when you compare things that are different. Humans are wired to notice differences, and the clever use of contrast can support powerful interactions. Contrast can be achieved in simple ways by utilising elements such as colour and space, and in conjunction with other principles such as proportion and scale." - (School Resources, 2020)</ol>
	<ol>
		- Repetition: "The principle of repetition provides predictability through the reusability of elements, and is commonly used in data-driven solutions. The repeated elements could be page constructs, sections or product layouts. This allows users to learn the user environment and predict where they will be able to source information they require." - (School Resources, 2020)</ol>
	<ol>
		- Alignment: "Alignment is a principle of design that is conducive to how users infer information from a layout. Alignment of images, text and objects provides structure, eliminates potential haphazardness and allows the user to effectively scan information." - (School Resources, 2020)</ol>
	<ol>
		- Proximity: "When presented with information, users will mentally group together elements that are close to each other in a space. It is suggested that many users 'clump' these into a summarised object. It is important to keep this in mind when developing a data-rich user experience. When data is placed close to other data, a relationship is often inferred based on a user's understanding of the logical layout of data. Changing the physical proximity of the data changes its potential meaning and how a user interprets it. This is an important consideration in delivering meaningful data to a user." - (School Resources, 2020)</ol>     
	<ol>
		- Balance: "Balance in an interface refers to a sense of equilibrium and symmetry in the eyes of the user, allowing the user to effortlessly interpret the interface. Balance is sometimes informal — meaning it isn't exact, and is more of a general appreciation of perspective. Balance in a web context may mean simply that the breakdown of the page shows symmetry in relation to chunks of detail." - (School Resources, 2020)</ol>

</li> <br>
	
* **Usability Elements**
	<ol>
		- Space: "Space can be used to support meaning and to zone groups of data. It can be used consistently to develop predictability throughout a user experience. It should not be considered to be just negative or blank. An interface without the use of structured space could be considered by a user to be too busy, confusing and not learnable." - (School Resources, 2020)</ol>
	<ol>
		- Line: "The use of the line element in interfaces is well defined and is naturally applied in the principles of alignment, proximity and hierarchy. A line can be thought of as a starting place, a marker or trigger to change. A simple horizontal line with textural and tone features within an interface such as a web page can provide separation or encapsulation." - (School Resources, 2020)</ol>
	<ol>
		- Colour and Tone: "The use of colour plays a significant role in developing data-driven applications and presentation of associated data. Aspects of colour that should be considered include: A: a consistent approach to colour choice throughout the application. This assists in branding and the predictability of the product for users. B: the compatibility of colours for ease of use. Some designers engage the colour wheel to identify compatible colour choices that support contrasting information as well as making the solution more accessible." - (School Resources, 2020)</ol>
	<ol>
		- Texture: "Texture is a truly artistic element of visual design and refers to the tactile or inferred visual features of an object. Texture can be used to assist in visual or physical improvements in accessibility, or in conjunction with other elements such as form and shapes to give emphasis or distinction. 
	" - (School Resources, 2020)</ol>  
	<ol>- Form: "Utilising the element of form within a user experience can give the feeling of depth and a multi-dimensional perspective. This could assist in highlighting components through the use of shadows on the surfaces or faces of objects. Form is usually applied in conjunction with other elements such as tone, texture and colour." - (School Resources, 2020)</ol>
	<ol>- Proportion and Scale: "Concepts such as the 'golden ratio' are used to demonstrate proportion in design work such as interfaces. This is a commonly occurring mathematical ratio that has been discovered to create aesthetically pleasing, natural-looking presentations." - (School Resources, 2020)</ol>
</li>

- - -
<br><br>

# Australian Privacy Act

* <i>Criteria: 
  * Explain
    * Australian Privacy Principles (2014) and ethics applicable to the use of personally identifiable or sensitive data from a digital systems perspective</i>

---

<br>

There are three main privacy principles that the exam will focus on, these consist of APP 1, 6 and 11

<li>
	<ol>
	    - APP 1 (Open and  transparent management of personal information): This principle highlights and prescribes efforts that organisations must take to meet the requirements of the Privacy Act and the Australian Privacy Principles in general. It provides advice to organisations about how to clearly communicate what information they collect, how they hold and use it, and who they can potentially disclose it to. This communication should also include ways in which individuals can access, correct or raise concerns about their information. The main communication strategy the principle suggests is the use of an organisational privacy policy. This policy must be accessible and free to all individuals at any time. For example, when accessing systems or exploring an organisational website, a privacy policy is generally an accessible document that is highlighted or mentioned. Adopting services provided by companies such as Apple also directs users back to privacy disclosure statements that they must acknowledge.
	</ol>
	<ol>
	    - APP 6 (Use or disclosure of personal information): This principle outlines how organisations may use personal information and in what circumstances they are allowed to disclose it. In a general sense, data must not be disclosed for any use other than its primary purpose unless consent is provided or other laws require it to be disclosed. In most circumstances, permission for third-party disclosures is listed among privacy policies that users are asked to agree to before they receive a service. In all other circumstances, information that is either de-identified or not considered personal or sensitive to an individual may be released. For example, if an organisation wanted to share elements of your personal data with a third-party research group, they would have to acknowledge this in their privacy policy or actively seek your consent. 
	</ol>
	<ol>
		- APP 11 (Security of personal information): This principle outlines the requirement on organisations to take reasonable steps to protect an individual's personal information from misuse, interference, loss or unauthorised access or disclosure. Methods of security 
	employed include technical and human processes such as encryption, access privileges and restrictions on how the information is accessed — for example, processes around how a customer can call an organisation and 
	gain access to their information. Questions that substantiate a user's identity are among the methods used at present. The principle also denotes that actions should be taken to destroy or de-identify data that the organisation 
	no longer needs.
	</ol>
</li>

<br><br>

---

# Networking

* <i>Criteria: 
  * Explain
    * Network transmission principles, including latency, jitter, guarantee and timeliness of delivery, and protocols relevant to the transmission of data over the internet, e.g. HTTP, HTTPS, FTP, VPN, streaming and broadcasting data packets
    * Methods for data exchange used to transfer data across networked systems including REST, JSON and XML

</i>

<br>

So what is a network? A network is essentially a group of computers that are connected, or linked, that are capable of sharing data, recourses and files with each other. This connection can be through many things but is most commonly linked though a cable/s, telephone lines, satellites or radio waves.

A useful comic to go along with this section can be found [here](https://jvns.ca/networking-zine.pdf). This comic will cover most of the content explained below in a fun condensed way. It is recommended you still read this section as it goes into more detail about certain topics.

---

**Latency**

Usually measured in milliseconds, latency is the  time it takes for data or a request to go from the source to the destination. Latency depends on the type of Network or the type of packets being transferred.

Latency can either be measured as the **Round Trip Time (RTT)** or the **Time to First Byte (TTFB)**:

- **RTT** is defined as the amount of time it takes a packet to get from the client to the server and back.

- **TTFB** is the amount of time it takes for the server to receive the first byte of data when the client sends a request.

<br>

**Jitter**

The deviation from true periodicity of a presumably periodic signal, often in relation to a reference clock signal. In clock recovery applications it is called timing jitter. Jitter may be caused by electromagnetic interference and crosstalk with carriers of other signals. Jitter can cause a display monitor to flicker, affect the performance of processors in personal computers, introduce clicks or other undesired effects in audio signals, and cause loss of transmitted data between network devices. The amount of tolerable jitter depends on the affected application.

<br>

**Protocols**

A protocol is is a system of rules that allows two or more entities of a communications system to transmit information via any kind of variation of a physical quantity. The protocol defines the rules, syntax, semantics and synchronisation of communication and possible error recovery methods. Protocols may be implemented by hardware, software, or a combination of both.

<li>

**List of common protocols**</li>

<ol>- HTTP: HyperText Transfer Protocol is used for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web.</ol>

<ol>- HTTPS: HyperText Transfer Protocol Secure is an extension of HTTP used for secure communication over networks. HTTPS is encrypted using TLS (Transport Layer Security). You can tell when your browser is communicating over HTTPS by the green lock icon in the address bar of most browsers. Most browsers also display a warning to the user when visiting a site that contains a mixture of encrypted and unencrypted content.</ol>

<ol>- FTP: File Transfer Protocol is used for the transfer of computer files between a client and server on a computer network. FTP users may authenticate themselves with a clear-text sign-in protocol, normally in the form of a username and password, but can connect anonymously if the server is configured to allow it. For secure transmission that protects the username and password, and encrypts the content, FTP is often secured with SSL/TLS (FTPS).  Setting up an FTP control connection is quite slow due to the round-trip delays of sending all of the required commands and awaiting responses, so it is customary to bring up a control connection and hold it open for multiple file transfers rather than drop and re-establish the session afresh each time. In contrast, HTTP originally dropped the connection after each transfer because doing so was so cheap. </ol>

<ol>- VPN: A Virtual Private Network extends a private network across a public network and enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network. Applications running across a VPN may therefore benefit from the functionality, security, and management of the private network. Encryption is a common, although not an inherent, part of a VPN connection.</ol>

</li>

<br><br>

---

# Next Section

* <i>Criteria: 
  * Recognise and describe encryption and authentication strategies appropriate for securing data transmissions and their differences
    * features of symmetric (Data Encryption Standard — DES, Triple DES, AES — Advanced Encryption Standard, Blowfish and Twofish) and assymetric (RSA) encryption algorithms
    * How data compression, encryption and hashing are used in the storage and transfer of data</i>

- - -



<br>

<br>

---

# References

* What is Encryption? | Types of Encryption. Cloudflare. (2020). Retrieved 3 September 2020, from [https://www.cloudflare.com/learning/ssl/what-is-encryption/](https://www.cloudflare.com/learning/ssl/what-is-encryption/).

- Encryption 101. EDUCAUSE. (2020). Retrieved 3 September 2020, from [https://www.educause.edu/focus-areas-and-initiatives/policy-and-security/cybersecurity-program/resources/information-security-guide/toolkits/encryption-101](https://www.educause.edu/focus-areas-and-initiatives/policy-and-security/cybersecurity-program/resources/information-security-guide/toolkits/encryption-101).

* Stubbs, R. (2020). An Overview of Symmetric Encryption and the Key Lifecycle. Cryptomathic.com. Retrieved 3 September 2020, from [https://www.cryptomathic.com/news-events/blog/an-overview-of-symmetric-encryption-and-the-key-lifecycle](https://www.cryptomathic.com/news-events/blog/an-overview-of-symmetric-encryption-and-the-key-lifecycle).

* Advanced Encryption Standard. En.wikipedia.org. (2020). Retrieved 3 September 2020, from [https://en.wikipedia.org/wiki/Advanced_Encryption_Standard](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard).

* S-box. En.wikipedia.org. (2020). Retrieved 3 September 2020, from [https://en.wikipedia.org/wiki/S-box](https://en.wikipedia.org/wiki/S-box).

* Blowfish (cipher). En.wikipedia.org. (2020). Retrieved 3 September 2020, from [https://en.wikipedia.org/wiki/Blowfish_(cipher)](https://en.wikipedia.org/wiki/Blowfish_(cipher)).

* Katz, A., Ng, A., Bourg, P., William, C., Ross, E., Khim, J., & Kau, A. (2020). RSA Encryption | Brilliant Math & Science Wiki. Brilliant.org. Retrieved 3 September 2020, from [https://brilliant.org/wiki/rsa-encryption/](Brilliant.org. Retrieved 3 September 2020, from https://brilliant.org/wiki/rsa-encryption/).

* PMTEducation. (2020). OCR Computer Science A Level [Ebook] (1st ed., pp. 3-6). Retrieved 4 September 2020, from [https://pmt.physicsandmathstutor.com/download/Computer-Science/A-level/Notes/OCR/1.3-Exchanging-Data/Advanced/1.3.1.%20Compression,%20Encryption%20and%20Hashing.pdf](https://pmt.physicsandmathstutor.com/download/Computer-Science/A-level/Notes/OCR/1.3-Exchanging-Data/Advanced/1.3.1.%20Compression,%20Encryption%20and%20Hashing.pdf).

* Nielsen, J. (2020). Usability 101: Introduction to Usability. Nielsen Norman Group. Retrieved 4 September 2020, from [https://www.nngroup.com/articles/usability-101-introduction-to-usability/](https://www.nngroup.com/articles/usability-101-introduction-to-usability/).

* 2020 Guide to Network Latency (2020). Retrieved 3 September 2020, from   [https://www.dnsstuff.com/network-latency](https://www.dnsstuff.com/network-latency)

* Communication Protocol (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/Communication_protocol](https://en.wikipedia.org/wiki/Communication_protocol).

* *HTTPS*. En.wikipedia.org. (2020). Retrieved 6 September 2020, from https://en.wikipedia.org/wiki/HTTPS.

* HTTP.  En.wikipedia.org. (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/HTTP](https://en.wikipedia.org/wiki/HTTP)

* FTP. En.wikipedia.org. (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/FTP](https://en.wikipedia.org/wiki/FTP)

* Jitter. En.wikipedia.org. (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/Jitter](https://en.wikipedia.org/wiki/Jitter)

* VPN. En.wikipedia.org. (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/VPN](https://en.wikipedia.org/wiki/VPN)

* *Chapter 6: APP 6 — Use or disclosure of personal information*. OAIC. (2020). Retrieved 7 September 2020, from  https://www.oaic.gov.au/privacy/australian-privacy-principles-guidelines/chapter-6-app-6-use-or-disclosure-of-personal-information/.

* *Read the Australian Privacy Principles*. OAIC. (2020). Retrieved 7 September 2020, from  https://www.oaic.gov.au/privacy/australian-privacy-principles/read-the-australian-privacy-principles/.

* *Guide to securing personal information*. OAIC. (2020). Retrieved 7 September 2020, from  https://www.oaic.gov.au/privacy/guidance-and-advice/guide-to-securing-personal-information/#ftn4.

* *Chapter 1: What is a Network?*. Fcit.usf.edu. (2020). Retrieved 7 September 2020, from https://fcit.usf.edu/network/chap1/chap1.htm.

* Singh, S. (1999). *The Code Book: The Science of Secrecy from Ancient Egypt to Quantum Cryptography* (1st ed.). Fourth Estate and Doubleday.

* Rodriguez-Clark, D. (2020). *Frequency Analysis: Breaking the Code*. Crypto Corner. Retrieved 7 September 2020, from  https://crypto.interactive-maths.com/frequency-analysis-breaking-the-code.html.

* Rodriguez-Clark, D. (2020). *Polyalphabetic Substitution Ciphers*. Crypto Corner. Retrieved 7 September 2020, from https://crypto.interactive-maths.com/polyalphabetic-substitution-ciphers.html.

* *Vigenère cipher*. En.wikipedia.org. (2020). Retrieved 7 September 2020, from https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher.

* *Gronsfeld Cipher*. Rumkin.com. (2020). Retrieved 7 September 2020, from http://rumkin.com/tools/cipher/gronsfeld.php.

  
