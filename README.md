
#Sign in

# Installation

Add in package.json

"gl-sign-in": "github:MihajloFD/test-miki-component",
npm install

## Usage
import SignInComponent from 'gl-sign-in';
add url and style like this
 <SignInComponent
          url=''
          errorMessageStyle='error-m'
          btnActiveStyle='btn btnActive'
          btnCustomStyle='btn'
          sighInForm='sighInForm'
/>
Style
.parent{
  position: relative;
  .sighInForm{
    position: absolute;
    top:39px;
    background-color: blueviolet;
    z-index: 150;
    width: 350px;
  }
  .btn{
    background-color: coral;
    color: greenyellow; 
  }
  .btnActive{
    background-color: royalblue;
    color: wheat; 
  }
  .error-m{
    padding: 10px 30px;
    background-color: yellowgreen;
    color: red;
  }
}