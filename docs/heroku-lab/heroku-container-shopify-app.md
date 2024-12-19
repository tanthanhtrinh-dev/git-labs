
# Set up hosting with Heroku container

[Ref deployment:](https://shopify.dev/docs/apps/deployment/web)

```shell
heroku login

```
```shell
git push heroku main
```

```shell
heroku container:login
```

### Create an app in Heroku:
```shell
heroku create -a tpf-shopify-integrate-mso -s container
heroku create -a tpf-shopify-integrate-rbar -s container
heroku create -a tpf-shopify-integrate-hl -s container
heroku create -a tpf-shopify-integrate-gmsv -s container
heroku create -a tpf-shopify-integrate-tfr -s container
heroku create -a tpf-shopify-integrate-wau -s container
heroku create -a tpf-shopify-integrate-bft -s container
heroku create -a tpf-shopify-integrate-yae -s container
heroku create -a tpf-shopify-integrate-rbarv -s container
heroku create -a tpf-shopify-integrate-scs -s container
heroku create -a tpf-shopify-integrate-bcn -s container
```
### Create an container in heroku
```shell
heroku create -a membership-discount-tfr -s container
```

### Add remote
```shell
git remote add heroku-rbarv https://git.heroku.com/tpf-shopify-integrate-rbarv.git
git remote set-url heroku-rbarv https://git.heroku.com/tpf-shopify-integrate-rbarv.git
```

```bash
git remote add heroku-scs https://git.heroku.com/tpf-shopify-integrate-scs.git
git remote add heroku-bcn https://git.heroku.com/tpf-shopify-integrate-bcn.git
```



### Deploy to Heroku
```shell
git push heroku-mso main
git push heroku-rbar main
git push heroku-hl main
git push heroku-gmsv main
git push heroku-tfr main
git push heroku-bft main
git push heroku-yae main
git push heroku-rbarv tantrinh/feature/rbarv:main
git push heroku-scs release/scs:main
git push heroku-bcn release/bcn:main
```
### Step 5: Update URLs in the Partner Dashboard

