# elm-review-config

Provides [`elm-review`](https://package.elm-lang.org/packages/jfmengels/elm-review/latest/) rules to REPLACEME.

## Provided rules

- [`JonDyerReview`](https://package.elm-lang.org/packages/jon-dyer/elm-review-config/1.0.0/JonDyerReview) - Reports REPLACEME.

## Configuration

```elm
module ReviewConfig exposing (config)

import JonDyerReview
import Review.Rule exposing (Rule)

config : List Rule
config =
    [ JonDyerReview.rule
    ]
```

## Try it out

You can try the example configuration above out by running the following command:

```bash
elm-review --template jon-dyer/elm-review-config/example
```
