# Movies list - Add Form

You have the `App` with the `MoviesList` and `NewMovie` form containing ready
to use `TextField` components. Learn how it works and implement an ability to
add movies from [IMDB](https://www.imdb.com/).

1. `NewMovie` should check if `title`, `imgUrl`, `imdbUrl`, `imdbId` are
entered when an input looses focus (`onBlur`) and show an error and a red
border if needed (learn how it it implemented in the `TextField`);
1. The `description` is optional;
1. Disable the submit button until all the required fields are filled (spaces should be trimmed);
1. Clear the form after adding a new movie.
1. Errors should not be shown after clearing the form (change its key to
reinitialize the form);

## Advanced validation
Implement the ability to add custom validation callback to the `TextField`.
Check if `imgUrl` and `imdbUrl` are valid URLs (you can use the next regex)

```js
const pattern = /^((([A-Za-z]{3,9}:(?:\/\/)?)(?:[-;:&=+$,\w]+@)?[A-Za-z0-9.-]+|(?:www\.|[-;:&=+$,\w]+@)[A-Za-z0-9.-]+)((?:\/[+~%/.\w-_]*)?\??(?:[-+=&;%@,.\w_]*)#?(?:[,.!/\\\w]*))?)$/;

```

## Demo Links

- [DEMO LINK](https://AndriiZakharenko.github.io/react_movies-list-add-form/)
