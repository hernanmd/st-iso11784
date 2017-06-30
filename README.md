# Introduction

ISO 11784 Project using Pharo Smalltalk

# Developing ISO 11784

To instal ISO 11784 package in Pharo Smalltalk (5.0) evaluate the following expression:

```smalltalk
Metacello new
	smalltalkhubUser: 'hernan' project: 'ISO11784';
	configuration: 'ISO11784';
	version: #bleedingEdge;
	load.
```

To install ISO 11784 plus the Senasa 754 code conversion application, please evaluate the following expression:

```smalltalk
Metacello new
	smalltalkhubUser: 'hernan' project: 'ISO11784';
	configuration: 'Senasa754App';
	version: #bleedingEdge;
	load
```smalltalk
