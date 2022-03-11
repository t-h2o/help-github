# help-github

## what that ?

my help memory for use github

## How pull request

### prerequisites

- have a github account
- need to change a projet
- unix terminal (mac os/linux)

### Fork s projet

- press the button "fork"
It's will create a copy of the projet in your profil 

### copy the project in the current directory

- `$ git clone https://github.com/<your-username>/<project-name>`
- `$ cd <projet-name>`

### Create and switch main's branch to a new one

- `$ git checkout -b "name_branch"`
- `$ git add file_modified_or_new`
- `$ git commit -m "your message about your modification"`
- `$ git push origin name_branch`

### go back on your browser

In your repo there is a button for pull request...
here there are... !

## verified a commit

### check the ressource

* [github](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification)
* [generate the key](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key)
* [add the key in your account](https://docs.github.com/en/authentication/managing-commit-signature-verification/adding-a-new-gpg-key-to-your-github-account)

install
[gpg](https://en.wikipedia.org/wiki/GNU_Privacy_Guard)

if you use v.2.1.17 or greater

generate the key
`gpg --full-generate-key`

else
`gpg --default-new-key-algo rsa4096 --gen-key`


`git commit -S -m "message"`
