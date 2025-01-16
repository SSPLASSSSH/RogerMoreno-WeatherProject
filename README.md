# Run in google colaboratory environment

## Setup/Check Environment
- !pip install streamlit

## Setup/Check Imported library
%%writefile ProyekAnalisisCuaca.py
- import streamlit as st
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns

# Run locally
!streamlit run ProyekAnalisisCuaca.py & npx localtunnel --port 8501


### Notes
if want to run in local IDE then it needs further adjustment
