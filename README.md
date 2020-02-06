[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/aspirebudgetingmobile/aspirebudgeting_android) 

# aspirebudgeting_android
[![Build Status](https://travis-ci.com/aspirebudgetingmobile/aspirebudgeting_android.svg?branch=master)](https://travis-ci.com/aspirebudgetingmobile/aspirebudgeting_android)

[![codecov](https://codecov.io/gh/aspirebudgetingmobile/aspirebudgeting_android/branch/master/graph/badge.svg)](https://codecov.io/gh/aspirebudgetingmobile/aspirebudgeting_android)

# What is Aspire Budgeting?
This is explained best by [u/Sapphire_Rapids](https://www.reddit.com/user/Sapphire_Rapids/), the creator of the Aspire Budgeting Google Sheet on his website [AspireBudget.com](https://aspirebudget.com/)
> Aspire is an envelope-style budgeting spreadsheet. Its primary goal is to give you the power and ability to be proactive with your finances - all in a delightfully designed Google Sheet. With Aspire, you can see your budget with just a glance, quickly add transactions as you make them, and run reports to get new insights on your spending.

# Aspire Android App
This is an independent project to develop a cleaner mobile interface to interact with the Aspire Google Sheet. The official [Google Sheets](https://play.google.com/store/apps/details?id=com.google.android.apps.docs.editors.sheets) app while truly powerful does not provide a good experience for a sheet of this kind. 

This project's design would be based on [Aspire iOS project](https://github.com/mohitathwani/aspirebudgeting). The goals and phases for this project are similar with the iOS counterpart. 

# Project Goals
The goal of this project is simple. It is to foster a positive learning environment for anyone in the field of Android development. 

The project should use the latest APIs available and have a clean, simple and a smooth user experience. 

The project will be split up into 4 phases. 

## Phase 1

1. Ability to connect to Google Drive via The Google Sheets SDK. 
2. Ability to read data points of interest from the Dashboard tab of the Aspire Sheet. 
3. Google Assistant Integration. For example, “Ok Google, how much can I spend on groceries?”
4. Integration with Android widgets. 
5. Fastlane integration for beta deployments, CI/CD, screenshot creation and beta tester sign up sheet. 
6. No data will be cached in Phase 1. The goal of the next few phases will be to build a solid privacy guideline and strategy. 

## Phase 2

1. Ability to add Transactions. 
2. Ability to perform Category Transfers.
3. Building a privacy guideline and strategy with the community enhance user experience using caching. 

## Phase 3

1. Data synchronization. 
2. Efficient strategy for merging data and conflict resolution between data on the cloud and on the device. 

## Phase 4

1. A complete on boarding flow right from copying the sheet from the Aspire website to the users account and entering all the required data in the Configurations tab. 

Phase 2(3) and Phase 3(1) and Phase 3(2) are too high level at this point and will require some research and expertise. 

# Code Quality

The project will use the highest standards in terms of code quality and architecture. We should strive for ~85% code coverage using Unit Tests and UI Tests.

