Mono: moim-front

Basic environment:
Node: 19.7.0

# Git clone을 했다면

```bash
~ cd mono-repo-test
npx lerna bootstrap --hoist
```

modules:

1. moim-web ( node 15)
   ; react
   ; redux

2. moim-components ( node 15)
   ; react
   ; styled-components
   ; material-ui
3. moim-hub ( node lts)
   ; nextjs

참고 POST

- https://pks2974.medium.com/mono-repo-%EB%A5%BC-%EC%9C%84%ED%95%9C-lerna-%EA%B0%84%EB%8B%A8-%EC%A0%95%EB%A6%AC%ED%95%98%EA%B8%B0-65c22029988
