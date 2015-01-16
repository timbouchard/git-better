# git-better
git better at git

--

```bash
for remote in `git branch -r `; do git branch --track $remote; done
```

```bash
for remote in `git branch -r `; do git checkout $remote ; git pull; done
```

### Installation

**Install Node Dependencies**

```bash
$ npm install
```

**Start the Node Server**

```bash
$ npm start
```

**View Your Project Dammit**

```bash
http://localhost:5000
```