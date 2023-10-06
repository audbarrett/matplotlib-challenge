# matplotlib-challenge
Challenge 5 - Matplotlib

# Description: Analysis of drug trial data tracking mice tumor response to several drug regimens. 

# Credits - Help received from class TAs, AskBCS, and tutor (Kourt Bailey). Code snippet received from Learning Assistant:
duplicate_mouse_ids = study_data_complete.loc[study_data_complete.duplicated(subset=['Mouse ID', 'Timepoint']),'Mouse ID'].unique()
duplicate_mouse_ids
  
