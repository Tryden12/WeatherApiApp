# Weather API App
This is a simple REST API app that displays weather information based on JSON data.

It is built using Java and includes a legacy ListView usage. The reasoning behind using ListView 
over RecyclerView is for two reasons. 
1. The volume of data being sent to screen will never exceed a list greater than 5
2. To familiarize myself with ListView