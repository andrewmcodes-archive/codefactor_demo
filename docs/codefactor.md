# CodeFactor

## Tutorial

We will be creating a demo app to showcase how to utilize CodeFactor on your projects. The completed code can be found [here](https://github.com/andrewmcodes/codefactor_demo) if you'd like to just look over that.

If you'd like to build it together, let's get started!

### Setup

Let's create a new Rails app and `cd` into it:

```sh
rails new codefactor_demo
cd codefactor_demo
```

Install dependencies:

```sh
bundle install
yarn install
```

And setup the database:

```sh
bin/rails db:setup
```

Now, let's start the Rails server:

```shell
rails s
```

If you want to run the `webpack-dev-server`, run this in another tab:

```shell
bin/webpack-dev-server
```

If you navigate to `localhost:3000` in your browser, you should see the Rails welcome page:

![rails_welcome_page](https://dev-to-uploads.s3.amazonaws.com/i/prwqk92m70wgn1ddk1d6.jpg)

### Create Repository

Open GitHub and create a new repository. I named mine `codefactor_demo`.

Open your command line again and let's upstream our code.

```sh
git add .
git commit -m "first commit"
git remote add origin https://github.com/YOUR_USERNAME/codefactor_demo.git
git push -u origin master
```

Your code should now be online in your repo.

### Configuration

### Test it out

## Summary

### Helpful links

Happy coding!
