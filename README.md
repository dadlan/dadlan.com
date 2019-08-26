# dadlan.com

## Dev environment:
1. Install [Hugo]((https://gohugo.io/content-management/organization/)
`brew install hugo`
2. Add content, example:
`hugo new posts/dadlan-2k18.md`
3. Run local environment (and display drafts)
`hugo serve -D`
4. Modify the content, make sure you modify draft line to be true, then check contain with `hugo serve`

## Deployment

Deployment is now covered by github actions (deploys to github pages).
