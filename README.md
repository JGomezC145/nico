# Previendo
{no}


```js
  hen(snapshot => {
      snapshot.docs.forEach(docs => {
        createPost(
          docs.data().postName,
          docs.data().createdAt,
          docs.data().postContent,
          docs.data().imgSource,
          docs.id,
          docs.data().likes
        );
      });
```
