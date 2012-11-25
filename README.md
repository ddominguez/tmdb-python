#How to use:

    import tmdb

    themoviedb = tmdb.TMDB(YOUR_API_KEY)

    # get movie info
    movie_data = themoviedb.movie_search('The Dark Knight')
    movie_id = movie_data['results'][0]['id']
    print themoviedb.movie_info(movie_id)

    
    # get person info
    person_data = themoviedb.person_search('Christian Bale')
    print themoviedb.person_info(person_id)