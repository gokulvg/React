# React

JXS - javascript XML,

How jsx code is rendered
  JSX code first converted into React.createElement equalent code and the this code is converted into React JS object and this is converted into HTML code, This convertion is happening in Babel.

In react we know we can write code like
  const data = api.getapiData();
  and then assign the data value directly into the JSX, But what if the api is affected by thrid person? then there is a possiblity thet the thrid person can run js code and access many of data from the browser,
  But the good thing is that JS compiler prevent this from happening.The js code will be santised.so no malicious codes can be run inside js.

  
