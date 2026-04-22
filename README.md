Site: https://jaketerry28.github.io/cs239-final/

Team: Jake Terry, Vaughn Cox, Quentin Beverly


---

We decided on building an interactive museuem on encryption. 

Team members contributions were as follows:

Quentin Beverly - gathering reliable sources, editing transcripts

Vaugn Cox - writing the transcripts for different sections

Jake Terry - html/css styling, building the interactive script section, secret level, transcripts

We used Twinery with the Sugarcube story framework strictly for implementing a javascript script for an interactive decryption/encryption section using the Caesar cypher with a 3 letter shift. Since sugarcube doesn't support markdown like the standard Harlowe story format, we had to use html and css styling for the transitions and effects.

---

>Framework

Encryption
# Welcome to the Digital Museum of Encryption

(transition:"pulse")[*Hello! This is an interactive museum to help you explore various topics about encrpytion including what encrpytion is, the histroy of history, how it works, how we use encrpytion every day, and an interactive exhibit that will hide your messages in real time.*]

(after:5s)[(animate:?passage's links, "rumble")]


Exhibit 1: (t8n-depart:"blur")[[What Is Encryption?]] 

Exhibit 2: [[History of Encryption]] 

Exhibit 3: [[How Encryption Works]] 

Exhibit 4: [[Encryption in Everyday Life]] 

Exhibit 5: [[Limits, Risks, and Ethics]] 

[[Interactive Encrypter]]



# What is Encryption?

<img src = "https://www.clickssl.net/wp-content/uploads/2023/02/how-does-encryption-works.jpg"
alt = "encrpytion"
height = auto
width = auto />

**Encryption** - the process of transforming readable *plain-text* into unreadable *cipher-text* to mask, hide, or obscure sensitive information. By applying a set of rules, algorithms, or keys, encryption changes information into a form that cannot be easily understood by unauthorized people.

Put plainly, encryption is a way of locking information so unauthorized people cannot understand it even if they get access to it. Rather than preventing access altogether, encryption makes stolen or intercepted data useless unless the person viewing it also has the correct key or method to decode it.

Deeper Dive: [[Plaintext vs ciphertext]]
Deeper dive: [[Why people encrypt information]]
# Encryption in Everyday Life

[[Text messaging]]
[[Online banking]]
[[Passwords]]
[[HTTPS / secure websites]]
# How Encryption Works

Theres many ways encrpytion is achieved


[[Keys]]
[[Symmetric encryption]]
[[Asymmetric encryption]]
[[Public key / private key basics]]
# History of Encryption

Encryption has existed in many forms throughout history. Early methods relied on simple letter substitutions or rearrangements, while modern encryption uses complex mathematical algorithms to protect digital communication, financial transactions, passwords, and private files. Whether used in ancient warfare or modern internet security, the goal remains the same: to preserve confidentiality and protect information from unwanted eyes.

[[Caesar cipher]]
[[Enigma / wartime cryptography]]
[[How encryption evolved over time]]
# Limits, Risks, Ethics

[[Weak passwords]]
[[Human error]]
[[Privacy vs surveillance]]
[[Can encryption be misused?]]

## Plaintext vs Ciphertext
## Why people encrypt information

Encryption can protect data at rest, in transit and while being processed, regardless of whether the data is in a computer system on-premises or in the cloud. For this reason, encryption has become critical to cloud security efforts and cybersecurity strategies more broadly.

According to the IBM® 2025 Cost of a Data Breach report, organizations that use encryption can reduce the financial impact of a data breach by over USD 200,000. 

Source: <a href="https://www.ibm.com/think/topics/encryption#:~:text=organizations%20that%20use%20encryption%20can%20reduce%20the%20financial%20impact%20of%20a%20data%20breach%20by%20over%20USD%20200%2C000" target="_blank">
  IBM Encryption Article
</a>

## Caesar cipher
## Enigma / wartime cryptography
## How encryption evolved over time
## Keys

### Public Key

### Secret Key
## Symmetric encryption
## Asymmetric encryption
## Public key / private key basics
## HTTPS / secure websites
## Passwords
## Online banking
## Text messaging
## Can encryption be misused?
## Human error
## Privacy vs surveillance
## Weak passwords
