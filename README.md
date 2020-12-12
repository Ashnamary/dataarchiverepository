#Import pandas - import pandas as pd
#youtube_data dataset used needed to be set in utf-8 format, therefore encoding is done. - df_youtubedata = pd.read_csv("youtube_dataset.csv",encoding='utf8')
#As per the requirement top 1000 data is loaded. - df_top_1000 = df_youtubedata.head(1000)
#find distinct channel type using unique() function- df_top_1000['channeltype'].unique(). Then all the distinct channels listed in the dataset are listed below.
#Display channeltype count with name to know exact number of channels in easch count.- channeltype_count2 = channeltype_distribution(df_top_1000,'channeltype','name')
#Finally the top 1000 values needed to be loaded into another csv file. df_top_1000.to_csv('Final1000.csv') - This creates another csv file Final1000 in the system.
