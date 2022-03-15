# Network

A computer network is a set of computers sharing resources located on or provided by network nodes. The computers use common communication protocols over digital interconnections to communicate with each other. These interconnections are made up of telecommunication network technologies, based on physically wired, optical, and wireless radio-frequency methods that may be arranged in a variety of network topologies.

#### OSI Model

The Open Systems Interconnection model (OSI model) is a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.

OSI Model consists of

#### Application 

This layer is closest to the end user
Interacts with software applications, for example web browser(Brave, Firefox, Chrome, etc)
HTTP and HTTPS are layer 7 protocols
https://www.silkroad.com

Functions of Layer 7 include:

identifying communication partners
Synchronizing communication

#### Presentation

Data in the application layer is in application format
it needs to be translated to a different format to be sent over the network

the presentation layer's jon is to translate between application and network formats

for instance encryption of data as it is sent, and decryption of data as it is received

Also translates between different applcation layer formats

#### Session 

Controls dialogues(sessions) between commanicating hosts

Establishes, manages, and terminates connections between the local application (for instance, web browser) and the remote applcation (for instance youtube, isro) 

#### Transport

Segments and reassembles data form communcations beteen and hosts

Breaks large pieces of data into smallar segments which can be more easily sent over the network and are less likely to cause transmission problems if error occure 

privide host-to-host communication

#### Network 

Provides connectivity between end hosts on different networks (ie outside of the LAN)

Provides logical addressing (IP addresses)

Provides path selection between source and destination

Routers operate at layer 3

#### Data Link 

Provides node to node connectivity and data transfer (for instance  PC to switch, switch to router, router to router)

Defines how data is formatted for transmission over a physical medium (for instance copper UTP cables)

Detects and(posssiby) cirrects Physical Layer error

Users Layer 2 addressing Separate form Layer 3 addressing

#### Physical


#### TCP/IP Suite

The Internet protocol suite, commonly known as TCP/IP, is the set of communications protocols used in the Internet and similar computer networks. The current foundational protocols in the suite are the Transmission Control Protocol (TCP) and the Internet Protocol (IP).


#### Server

A server is device that provices function and service to the end users

#### Client

A device that accesss a service mode available by server

NOTE: A same device can be a client in some situations, and a server in other situations

#### Subnet

A subnetwork or subnet is a logical subdivision of an IP network. The practice of dividing a network into two or more networks is called subnetting. Computers that belong to the same subnet are addressed with an identical most-significant bit-group in their IP addresses.

#### Router

have fewer network interfaces then switch
are used to provide connectivity between LANS
are therefore used to send data over the internet

#### Switch

have many network interfaces/ports for end hosts to connect to (usually 24+)
provide connectivity to hosts within thwe same LAN 
do not provide connectivity between LANs/over the internet

#### Firewall

monitor and control network traffic based on configured rules
can be placed inside the network or outsite the network
are known as Next-Generation Firewalls when they include more modern and advanced filtering capabilites

#### Ethernet

Ethernet is a collection fo network protocols/standards

#### Lan

A local area network (LAN) is a computer network that interconnects computers within a limited area such as a residence, school, laboratory, university campus or office building.

#### Vlan

A virtual LAN (VLAN) is any broadcast domain that is partitioned and isolated in a computer network at the data link layer (OSI layer 2). LAN is the abbreviation for local area network and in this context virtual refers to a physical object recreated and altered by additional logic

#### Ip
An Internet Protocol address (IP address) is a numerical label such as 192.0.2.1 that is connected to a computer network that uses the Internet Protocol for communication.[1][2] An IP address serves two main functions: network interface identification and location addressing.

# Docker 

way to package software, so it can hardware

docker consists of Docker file, Docker image, Docker container



docker file is a blueprint for building a docker image

docker image is a template for running docker container

docker container is a run process



docker reprodue the envirement

for instance: in over case node application  is required to install some dependencies it works my machine but some else with different machine trying to run with the different machine of node it might brake, the whole point of is to solve problems like this by reproducing the environment

the developer how to create the software can define the environment  with the docker file then any developer at that point can use dockerfile to rebuild the environment which is stored as an immutable snapshot known as image, images can be uploaded to the cloud both the public and private registries then any developers or servers run the software can pull the image down to create  a container which is just a process of that image another word one image file can be used to spine same process multiple times and multiple places and it that point tools like Kubernetes comes in play, to  scale containers to infinite workload





# Git 

git is system for keeping track of changes that happen across a set of files

keep track of all changes that happen to files

for example you working of code base, you take a snap shot or commits of current status of the file, every commit has a unique id and it's links to parent id and this means we can traval back time  privous version of file




# API

Application programming interface or API is a way for two computers to talk to each other or  between computer programs


using an API is just like using a website in your browser but started clicking button filling forms, you write code to explicitly  request data for the server, for instance
 
 we can visit isro websites to lock at astroid images or we can use reset API to request raw JSON data
 
 
 
 
# Linux

#### Kernal

The kernel is a computer program at the core of a computer's operating system and generally has complete control over everything in the system. It is the portion of the operating system code that is always resident in memory, and facilitates interactions between hardware and software components.


#### OS

An operating system (OS) is system software that manages computer hardware, software resources, and provides common services for computer programs.

Time-sharing operating systems schedule tasks for efficient use of the system and may also include accounting software for cost allocation of processor time, mass storage, printing, and other resources.

For hardware functions such as input and output and memory allocation, the operating system acts as an intermediary between programs and the computer hardware,[1][2] although the application code is usually executed directly by the hardware and frequently makes system calls to an OS function or is interrupted by it. Operating systems are found on many devices that contain a computer – from cellular phones and video game consoles to web servers and supercomputers.


#### Bash

command language interpreter for interacting with a computer from the command line it suroundes the operating system kernal

it provides a prompt are we can type command which will interpreted by shell and excuted on the opertaing system






# Python 


python is a interpreted, object oriented , high level programming language with dynamic semantcs

it is  commanly used to build server-side application like web apps with django and flask framework language of choice BIG Data analysis and machine learning 

The Python interpreter and the extensive standard library are available in source or binary form 

Python supports modules and packages

Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance

current version of python is 3,

python program file ends with .py extention


python modules 

A Python module is a file containing Python definitions and statements. A module can define functions, classes, and variables. A module can also include runnable code


#### For 

A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

#### while

Python While Loop is used to execute a block of statements repeatedly until a given condition is satisfied. And when the condition becomes false

## If

Python if Statement is used for decision-making operations. It contains a body of code which runs only when the condition given in the if statement is true. If the condition is false, then the optional else statement runs which contains some code for the else condition.

## Package

A package is basically a directory with Python files and a file with the name __init__ . py. This means that every directory inside of the Python path, which contains a file named __init__ . py, will be treated as a package by Python.

## Array

A Python Array is a collection of common type of data structures having elements with same data type. It is used to store collections of data. In Python programming, an arrays are handled by the “array” module. If you create arrays using the array module, elements of the array must be of the same numeric type.

# OOP

#### Polymorphism: 

The word polymorphism means having many forms. In programming, polymorphism means the same function name (but different signatures) being used for different types.

#### Abstraction:

Abstraction is used to hide the internal functionality of the function from the users. The users only interact with the basic implementation of the function, but inner working is hidden

#### Inheritance:

Inheritance is the capability of one class to derive or inherit the properties from another class.

#### Encapsulation:

Encapsulation is one of the fundamental concepts in object-oriented programming (OOP). It describes the idea of wrapping data and the methods that work on data within one unit.


#### Interpreter

An interpreter is a kind of program that executes other programs. When you write Python programs , it converts source code written by the developer into intermediate language which is again translated into the native language / machine language that is executed.


#### Class

In object-oriented programming, a class is an extensible program-code-template for creating objects, providing initial values for state (member variables) and implementations of behavior


####### Tuple

Tuple is an ordered collection of elements enclosed within () 

#### List

List is an ordered collection of elements enclosed within []

####### Dictionary

Dictionary is an unordered collection of key-value pairs encloded with {}

#### strings

Strings are sequence of characters enclosed within single quotes(''), duotes to tri





# Database

database is nothing but organized collection of data

#### SQL

it provides a prompt are we can type the command which will be interpreted by shell and executed on the operating system

SQL is a database computer language designed for the retrieval and management of data in a relational database. SQL stands for Structured Query Language.


#### foregin key

A foreign key is a set of attributes in a table that refers to the primary key of another table. The foreign key links these two tables.



#### Primary key

In the relational model of databases, a primary key is a specific choice of a minimal set of attributes (columns) that uniquely specify a tuple (row) in a relation (table).[a][1] Informally, a primary key is "which attributes identify a record," and in simple cases constitute a single attribute: a unique ID



# HTML

The HyperText Markup Language, or HTML is the standard markup language for documents designed to be displayed in a web browser.


# CSS

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML.


# Node.js

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

platform to run JavaScript on the server i.e outside the browser







# Cryptography

cryptography is technic such as encryption and decryption

it is the study of techniques for secure communication between sender and receiver

#### Encryption

encryption is a process of converting normal text into cyper text

#### Types of Encryption 

#### Symmetric encryption

it is a type of encryption that uses the some secret ket for encryption as well as decryption

#### Asymmetric encryption

it is a type of encryption in which public key is used for encryption and private key is used for decryption

plain text -> Cipher text -> plain text
.	public key       private key
.	encryption       decryption

Encryption Algorithms and protocols

### Encryption Protocols

TLS/SSL
IPsec
SSH
PGP




# Parameters

parameters are the variable inputs that used in funtion definations





#### Brute force attack

it is a trial and error procedure used by hackers to crack passwords and encryption keys to gain unauthorized access




#### Types of Cyber Security

Network Security
information Security
Application Security
Cloud Security
Internet of ThingS Security
Mobile Security

#### What is a Network


A network is a connection between two or more devices such aa computres, webcams, laptops, printers, etc. to share data and files via an internet connection


#### What is Network Security

Network Security is the process of taking precautionary measures to protect the devices from unauthotized access modification, or destruction

#### Types fo Network Security attacks

Data threat
insider threat
malware attack
password attack
social engineering attack

#### Network Vulnerabilities

Improperly installed hardware/software
Operating Systems that have not been updated
Complete  lack of physical security
insecure passworks/week passwords
Design flaws in a network
outdated or unpatched software application
check your firewall configuration
mobile device vulnerabilities

#### Tools used to ensure Network Security

Packet Crafters
web Scanners
Packer Sniffers
Intrusion Detection System
penetration testing Software

#### Network Security Protocols

TLS/SSL
IPsec
SSH
PGP
HTTPS
