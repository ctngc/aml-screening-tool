# aml-screening-tool
Python tool for AML screening: simple and multiple conditional forms, detection of matches against sanctions lists (exact and fuzzy matching), and detection of suspicious transaction patterns (structuring, unusual amounts).

# AML Screening Tool
A personal project that simulates daily AML compliance tasks using a database and Python coding: screening customers against a sanctions list and
detecting suspicious transactions.

## Features
- Loading and cleaning customer data (pandas)
- Exact and approximate screening (fuzzy matching with rapidfuzz) against sanctions lists (e.g., OFAC, SECO, EU Sanctions List, FATF Gray & Black Lists, etc.) 
- Detection of suspicious patterns in transaction history: structuring, unusual amounts, abnormal frequency
- Automatic generation of a multi-sheet Excel report with a summary

## Technologies
Python, pandas, rapidfuzz, openpyxl

## Context
Project undertaken to apply my Python skills to my experience in financial auditing and AML compliance within investment funds and private banking

