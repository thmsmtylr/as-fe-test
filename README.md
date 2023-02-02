# A&S FE developer test
## Setup
1. Create a new [Next.js](https://nextjs.org/) app in Typescript or Javascript using `npm` and `node@18`
2. Add [Tailwind](https://tailwindcss.com/) and [Radix UI](https://www.radix-ui.com/) as the styling UI strategy
3. Add `@axe-core/react` for accessibility

## API Querying & pagination
3. Retrieve a list of `100` popular movies from [The Movie DB](https://www.themoviedb.org/) using their [API](https://developers.themoviedb.org/3/getting-started/introduction)
4. The list of popular movies should be batched in groups of `20`
5. On page load return the first `20` results as a `5` column grid that includes the movie `cover art`, `title`, `realease date` and `rating`
6. Add a load more button that `onClick` returns the next `20` results until the list is exhausted. The button should be hidden when the end of the list has been reached

![Popular-Movies-—-The-Movie-Database-TMDB-](https://user-images.githubusercontent.com/5527769/216195797-a0dd80b4-8538-492e-8907-62b32b7f5712.png)

## Managing state
7. Clicking a movie item should open a [Radix UI Dialog](https://www.radix-ui.com/docs/primitives/components/dialog) that includes more information from the api about the movie
8. The layout and content can include anything you want

<img width="1502" alt="Screen Shot 2023-02-02 at 11 12 48 am" src="https://user-images.githubusercontent.com/5527769/216198173-7fd6ac42-ff7a-49d3-9e1c-707c45dafe51.png">

## Infrastructure
9. Deploy your app to any service you deem appropriate E.g. AWS

## Extra points
1. Make the list sortable using a Radix UI component E.g.

<img width="284" alt="Screen Shot 2023-02-02 at 10 53 03 am" src="https://user-images.githubusercontent.com/5527769/216194464-6361e132-1c7e-4460-b737-9961bab1044e.png">

2. Make the `title` of the movie items searchable

## Notes
- Use conventional commits
- You must be able to explain why you chose your deployment service
- The site should be accessible E.g. Lighthouse testing
- API error handling should be appropriate
- The readme should be updated to include any important information for setup and configuration
- The app should have no console errors in production and development
- Try to avoid adding third party tooling or libraries unless you can justify their usage
