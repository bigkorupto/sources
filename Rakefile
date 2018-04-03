require 'hoe'
require './lib/shilling/version.rb'

Hoe.spec 'shilling' do

  self.version = Shilling::VERSION

  self.summary = 'shilling (or schilling) on the blockchain! rock-solid alpine dollar from austria; print (mine) your own shillings; run your own federated shilling central bank nodes w/ public distributed (hyper) ledger book on the blockchain peer-to-peer over HTTP; revolutionize the world one block at a time with cryptos'
  self.description = summary

  self.urls    = ['https://github.com/bitshilling/bitshilling.tools']

  self.author  = 'Gerald Bauer'
  self.email   = 'ruby-talk@ruby-lang.org'

  # switch extension to .markdown for gihub formatting
  self.readme_file  = 'README.md'
  self.history_file = 'History.md'

  self.extra_deps = [
    ['sinatra', '>=2.0'],
    ['sass'],   ## used for css style preprocessing (scss)
    ['blockchain-lite', '>=1.4.0'],
    ['ledger-lite', '>=1.1.1' ]
  ]


  self.licenses = ['Public Domain']

  self.spec_extras = {
   required_ruby_version: '>= 2.3'
  }

end
