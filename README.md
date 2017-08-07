# rem2-loader
webpack rem2-loader

##how to use
  module: {
    loaders: [
      {
        test: /\.less$/,
        loader: 'style-loader!css-loader!less-loader!rem-loader?scale=0.015&fix=2&pm=im'
      }
    ]
  }
  
eg.:

less: 
  p {
    width: 20im;
  }


css:
  p {
    width: 0.427rem;
  }
