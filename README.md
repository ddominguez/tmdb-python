how to use:
---

    import tmdb

    themoviedb = tmdb.TMDB(YOUR_API_KEY)
    movie_data = themoviedb.movie_search('The Dark Knight')
    movie_id = movie_data['results'][0]['id']
    print themoviedb.movie_info(movie_id)