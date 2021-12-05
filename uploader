<?php
//https://github.com/NathanCHEFF/uploader-to-github-on-php.git
$name='';
$repo='';
$file='';


$token='';

$curl_url = $url;
$curl_token_auth = 'Authorization: token ' . $token;
$ch = curl_init($curl_url);

curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
curl_setopt($ch, CURLOPT_HTTPHEADER, array( 'User-Agent: $username', $curl_token_auth ));
curl_setopt($ch, CURLOPT_CUSTOMREQUEST, "PUT");
curl_setopt($ch, CURLOPT_POSTFIELDS,$data);

$response = curl_exec($ch);  
curl_close($ch);
$response = json_decode($response);

var_dump( $response );
?>
