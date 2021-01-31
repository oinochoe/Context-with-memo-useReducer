# TodoTemplate
# TodoHead

# TodoList

# TodoItem

# TodoCreate


# 배포
```
npm install gh-pages --save-dev
```

```
homepage: http://{사용자 이름}.github.io/{저장소 이름}
```

```
scripts: {
    ...
    predeploy: npm run build,
    deploy: gh-pages -d build
}
```

```
npm run deploy
```