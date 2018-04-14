FROM mongo:latest

COPY all.json /init.json
CMD mongoimport --host mongodb --db cityrun --collection Data --type json --file /init.json --jsonArray
