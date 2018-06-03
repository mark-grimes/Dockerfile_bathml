# bathml

Docker image for the [Bath machine learning mini-confrence](https://www.meetup.com/Bath-Machine-Learning-Meetup/events/250510966/) (python). The data for the conference is already in the /notebooks folder. If you want to have any persistent data you will need to share a folder, e.g.:

```
docker run --rm -it -v $PWD:/notebooks/tokeep -p 8888:8888 bathml
```

