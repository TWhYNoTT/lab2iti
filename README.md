# Lab 2 ITI

## Project Image
![Project Image](123.png)

### 1. How to Remove Branches Locally and Remotely

**Locally:**

To delete the `dev` and `test` branches locally.

```bash
git branch -d dev
git branch -d test
```

**Remotely:**

To remove the `dev` and `test` branches from the remote repository.

```bash
git push origin --delete dev
git push origin --delete test
```

### 2. How to Checkout Another Branch Without Committing Changes

To switch branches without committing my current changes.

```bash
git stash
git checkout dev
```

### 3. How to List Tags

To list all tags in my repository.

```bash
git tag
```

### 4. How to Delete a Tag Locally and Remotely

**Locally:**

To delete the `v1.9` tag locally.

```bash
git tag -d v1.9
```

**Remotely:**

To remove the `v1.9` tag from the remote repository.

```bash
git push origin --delete v1.9
```
