# Zendesk-API-Integration
Create API connection, get data, save in CSV format

The aim of this project was to get time_reply metric for Ticket by selected Date. Unfortunately Zendesk doesn't allow to do it in one step. That's why we need:

- Step 1: Specify date that you need. Get all Ticket IDs for this date

- Step 2: Get time_reply metric for each Ticket ID from Step 1

- Step 3: Merge two dataframes and save in CSV format 
