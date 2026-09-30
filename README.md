# Coffee Break
* When you're tired, try writing by hand.
* Delete all branches that have been merged into main.

```shell
git branch --merged | grep -v "main" | xargs git branch -d
```