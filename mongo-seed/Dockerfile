FROM mongo

ADD ./*.json /

CMD mongoimport --host mongodb --db dota --collection heroes --type json --file /heroes.json &&\
mongoimport --host mongodb --db dota --collection items --type json --file /items.json
