# homebrew-versions-1
elasticsearch 1.7.6 for brew install

to install just run:
> brew install thiswayq/homebrew-versions-1/elasticsearch17   

then just start using elasticsearch command
> elasticsearch

if you get "Error: The `brew link` step did not complete successfully" 
then you need to unlink the actual version of elasticsearch
> brew unlink elasticsearch
> brew link elasticsearch17
