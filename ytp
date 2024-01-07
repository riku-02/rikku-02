import streamlit as st
from pytube import Search

st.image('https://upload.wikimedia.org/wikipedia/commons/thumb/d/dd/YouTube_Premium_logo.svg/1280px-YouTube_Premium_logo.svg.png')
name = st.chat_input('Search Anything... | YT Premium Beta by Riku')

if name:

    s = Search(name)
    for v in s.results:
        st.text(v.title)
        st.video(v.watch_url)

    # get object keys
    # keys = "\n".join([k for k in s.results[0].__dict__])
    # print(keys)
