# GIT

```
echo "Hello world" | git hash-object --stdin
```

![image](https://github.com/user-attachments/assets/df433df4-bbea-44f3-a5a7-8c6fd5a8caba)

This command creates a Git hash (SHA-1) for the content "Hello world". SHA contains 40 characters

🔍 Breakdown:
echo "Hello world": prints the string Hello world.

|: passes that string to the next command.

git hash-object --stdin: takes the input and calculates the Git object hash for it.

✅ Why Use It?
Git uses hashes (unique IDs) to track files/content. This command shows what the hash would be if Git stored "Hello world" as a file.

SHA changes even one letter changes


Created repo → cloned → pushed some changes into main branch

![image](https://github.com/user-attachments/assets/af0762c2-2975-4cb8-90a1-787694c5e253)

```
git log
```

![image](https://github.com/user-attachments/assets/9296d380-5e05-443c-a30c-2b7b389e3a80)

```
git log --oneline
```

![image](https://github.com/user-attachments/assets/d280072d-6ff3-4f61-a1cb-6eee1a06890e)

```
git cat-file <commit_id> -p
```

Print information about SHA code

![image](https://github.com/user-attachments/assets/58fa2c89-967f-4cd9-9dec-01027f0c2b6d)

Repo → settings → branches → add classic branch protection → Branch name pattern : main → Require pull requests before merging → Request approvals → Create

```
git checkout -b karam-dosa
```

Creates new branch and change workspace into new branch

![image](https://github.com/user-attachments/assets/e0fecacd-19f0-42da-8816-44a839c2208c)

repo → settings → Collaborators → add people → add

John has to accepts the invitation to connect

Created pull request → new pull request → base:main←compare:karam-dosa → create

![image](https://github.com/user-attachments/assets/8ad46013-4a69-4c84-8c48-264fd56395b2)

Both accounts can have conversation about code or anything

![image](https://github.com/user-attachments/assets/438eb8c7-db40-48da-90c7-d3f9bdfd4b0c)

![image](https://github.com/user-attachments/assets/7f2c0548-92ee-40bb-bc99-a6f3a4190f57)

If everything was good, John will approve for pull request

Anyone(John or me) who hass access can merge this into main branch










