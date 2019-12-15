# GitLearning

## :gift: Aliases of git

- [ ] Previously need save :green_heart: variant into `settings file` etc: `~/.zshrc`, `~/.shrc`, `~/.bashrc`, 

|Alias| Git command| My using variant|
|-|-|-|
|`gb`|`git branch`|.. |
|`gc`|`git checkout`|..|

## :train: Works with Fork repo

<!-- Old notices from issue: https://github.com/vovs03/sabbath-school-lessons/issues/3 -->

## Удаление веток

- локально:
  - `git branch -D master`
  - `git branch -D stage`

- на удалённом репозитории:
  - `git push origin --delete <branchName>`<a name="howto"></a>
  - `git push origin --delete stage` :heart: 2018-12-28

## как работать в git с форком

:mega: https://github.com/OsArts/Bible-study

- Чтобы подгрузить в Ваш форк актуальные файлы из **первичного** репозитория Adventech  
нужно в ветке :warning: `stage` выполнить:  
  - :a: `git pull https://github.com/Adventech/sabbath-school-lessons stage`
  - :b: `git push -u origin stage`
  - :star: https://github.com/Adventech/sabbath-school-lessons/issues
- [x] :memo: https://github.com/deepmipt/dlschl/wiki/Git:-пошаговая-инструкция

### 

- :green_heart: `git commit -m "Add: :ru: ru/2019-02/05/teacher-comments.md  :memo: - :zero::five:"
` 
- `git commit -m "Add: :ru: ru/2019-02/07/inside-story.md :dove: - :zero::seven:"
`


## удаление последнего коммита

- https://githowto.com/ru/removing_commits_from_a_branch


`git log --pretty --graph --date=short`

### Алиасы

- https://githowto.com/ru/aliases

- :heart: `gb` = `git --no-pager branch` / Просмотр списка веток в терминале
- `git hist` hist = `log --pretty --graph --date=short`
- `gcm` = `git checkout master`
- `gcd` = `git checkout develop`
