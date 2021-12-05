# uploader-to-github-on-php

example how update the file on yours repos.

you needed get the token on here https://github.com/settings/tokens
 

$x = new upGithub('NathanCHEFF','token');// username and token
$x->setRepos('uploader-to-github-on-php');
var_dump( $x->getSHA('test1')); // return sha
var_dump( $x->uploadFile('test1','testtext1')); //upload new file 'test' with contents 'testtext'
