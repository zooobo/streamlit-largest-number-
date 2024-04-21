import streamlit as st

st.title('Find the Largest Number')

num1 = st.number_input('Enter first number:')
num2 = st.number_input('Enter second number:')
num3 = st.number_input('Enter third number:')

if st.button('Find Largest'):
    if num1 >= num2 and num1 >= num3:
        st.write(f'{num1} is the largest number.')
    elif num2 >= num1 and num2 >= num3:
        st.write(f'{num2} is the largest number.')
    else:
        st.write(f'{num3} is the largest number.')
