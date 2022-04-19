# NewPCK
## How to generate new *SSH KEY* for a new computer

*NOTE! Windows users: use git bash admin for a best solution

#### 1. ```git config --global user.name "username_xpto"```

#### 2. ```git config --global user.email "email_xpto@provider_xpto.com"```

#### 3. ```ssh-keygen``` and then hit 3 times '*ENTER button*'
 
#### 4. ```clip < ~/.ssh/id_rsa.pub``` (this will automatically copy the ssh key then you just need to paste it with ctrl + v)

#### 5. Put it into github.com > settings > new SSH KEY

## 6. DONE!
