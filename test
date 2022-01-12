import streamlit as st
import pandas as pd
import numpy as np
import time
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.figure_factory as ff
import altair as alt
from PIL import Image
import base64

st.write('hello,world!')
st.write('hello,world!???')
x1 = np.random.randn(200) - 2
x2 = np.random.randn(200)
x3 = np.random.randn(200) + 2

hist_data = [x1, x2, x3]
group_labels = ["Group 1", "Group 2", "Group 3"]
fig = ff.create_distplot(
    hist_data, group_labels, 
    bin_size=[0.1, 0.25, 0.5])

st.markdown("# plotly绘图")
st.plotly_chart(fig)
