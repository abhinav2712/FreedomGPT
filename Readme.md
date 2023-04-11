# Freedom GPT

Freedom GPT is an open-source desktop application built using Electron and React. It allows users to run alpaca models on their local machine. This repository contains the source code for the application.

### GitHub License
![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

### GitHub Release
![GitHub release](https://img.shields.io/github/release/ohmplatform/freedom-gpt-electron-app.svg)

### GitHub Stars
![GitHub stars](https://img.shields.io/github/stars/ohmplatform/freedom-gpt-electron-app.svg)

![GitHub All Releases](https://img.shields.io/github/downloads/ohmplatform/freedom-gpt-electron-app/total.svg)

# Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Cloning the repository](#cloning-the-repository)
- [Installing dependencies](#installing-dependencies)
- [Changing the API URL](#changing-the-api-url)
- [Building the application](#building-the-application)
- [Running the application](#running-the-application)

## Introduction

This is the repository for the Freedom GPT application. This application is built using
[Electron](https://www.electronjs.org/) and [React](https://reactjs.org/). It is a desktop application that
allows users to run alpaca models on their local machine.

## Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable)
- [Git](https://git-scm.com/downloads)

## Cloning the repository

To clone the repository, run the following command in your terminal:

`git clone https://github.com/<your username>/freedom-gpt-electron-app.git`

## How to install Yarn:

If your system doesnt have yarn installed, use this command first:

`sudo npm install --global yarn`

## Installing dependencies

To install the dependencies, run the following command in your terminal:

`yarn install`

## Changing the API URL

We are using `http://localhost:8889` as the API URL, you can change it in the file
`src/index.ts`

## Running the application

To run the application, run the following command in your terminal:

`yarn start`

## Building the application

To build the application, run the following command in your terminal:

`yarn package`

This will create a distributable package for your operating system, which you can then install and use.
