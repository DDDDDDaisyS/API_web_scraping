## Transport of London

This mini-project shows how to work with the API from [Transport of London](https://api.tfl.gov.uk/). The main goal is to practice different HTTP requests and extracting values from complex lists and nested dictionaries.

> #### Instruction
> Register for the API service to obtain an **Application ID** and **Key**. We should append these values as parameters `app_id` and `app_key` into each URL when sending the request.

`?app_id={app_id}&app_key={app_key}` should be appended to every URL in all HTTP requests. However, this API works **without** the `app_id` and `app_key` in case we can't register for some reason.

> #### Instruction
> Once you have your credentials ready, go to the file `mini-project-I.ipynb` and follow the instruction in there.


## Movies

> #### Instruction
> Register for the [API service](https://www.themoviedb.org/account/signup) to obtain the **API Key**. We will have to append this value as parameter `api_key` into each URL when sending the request.

Once we are registered we can check the documentation of this API [here](https://developers.themoviedb.org/3/account).

In this part of the project, we will look for information about our favorite movie and actors. We will learn something about each other tomorrow when we present results.
