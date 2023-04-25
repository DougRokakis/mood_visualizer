# What does this app do?
In this application the following occurs:
1.  glob is used to return all files specified as filepaths. 

2. The filepaths are then looped through, opened and read with the content from the reading stored in the content variable. 

3. The sentimentIntensityAnalyzer() stored in the analyzer variable is then used to assess the polarity scores of the content. 

4. The positivity scores are then appended to the empty positivty list and the negativity scores are appended to the negativity list.

5. The names of the text files are then stripped of their .txt file type and their folder location and stored in the dates variable.

6. With all that data being gathered it is now time to employ streamlit with the title("Diary Tone") and subheader("Positivity") established.

7. Plotly express is now utilized with the X-axis equated to the dates variable
and the Y-axis equated to the positivity variable.

8. With the aid of streamlit, a chart is plotted.

9. Steps 6-8 are repeated only now charting the "Negativity" of the diary entrees.

