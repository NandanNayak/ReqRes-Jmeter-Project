# ReqRes-Jmeter-Project

## Table of Contents

- [Introduction](#introduction)
- [mTLS communication using Jmeter](#mTLS-communication-using-Jmeter)
- [Resources](#resources)

## Introduction

This project contains a JMX file which performs GET, POST, PUT and DELETE operations against a server `reqres.in`. The server `reqres.in` is REST-API ready and responds to AJAX requests with responses. 

The Jmeter script `ReqResTesting.jmx` is an attempt to understand the basic functionality of Jmeter tool to perform REST calls against a server.

In this script, I have used a `ThreadGroup` to create a test suite to perform HTTP requests and assert the responses using the Status codes and text responses. The `ThreadGroup` also generates a `Results Tree` to analyze all the responses and assertions.

## Resoures

- [https://reqres.in](https://reqres.in)
- [How to run Jmeter ThreadGroups sequentially](http://www.mahsumakbas.net/run-jmeter-thread-groups-consecutively/)
