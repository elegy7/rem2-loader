# rem2-loader
webpack rem2-loader
fork from rem-loader

## how to use
    module: {
        loaders: [{
            test: /\.less$/,
            loader: 'style!css!less!rem2?scale=0.0135&fix=2&pm=rpx'
        }]
    }
## eg:
#### less(write):
    p {
       width: 20rpx;
   }

#### css(build):

    p {
        width: 0.27rem;
    }
