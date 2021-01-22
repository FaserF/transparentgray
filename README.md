# Transparent Dark Gray

## A transparent dark gray theme for Home Assistant 
> This is my first ever custom theme for Home Assistant and my first ever GitHub/HACS repository.<br /> 
Thanks to: https://github.com/JOHLC/transparentblue for his dark blue theme, where this theme is based on.

## General information
I am using the frontend extion [animated backgrounds](https://github.com/Villhellm/lovelace-animated-background). Thats the reason that I have removed a background from this theme. <br /> 
If you want one, please have a look below under Changing the background image. Maybe I will release a darkgray version with a background implemented.
As I am using this for my personal interest. Be aware, that I will only be giving limited support and wont accept all pull requests.

### Screenshots
**transparentgray.yaml**<br />
<img src="images/transparentgray1.png" alt="transparentgray.yaml" width="1000">

**transparentgray-other.yaml**<br />
<img src="images/transparentgray2.png" alt="transparentgray-other.yaml" width="1000">

## Button Colors
### transparentgray-other.yaml
If you prefer the Gray and Blue buttons (second screenshots), change the code as below:<br /> 
  #Switches<br /> 
  switch-checked-button-color: ''                                           #Switch On<br /> 
  switch-unchecked-button-color: 'var(--slightly-darker-text)'              #Switch Off<br /> 
  switch-checked-track-color: '#009FFF'                                     #Switch background when On<br /> 
  switch-unchecked-track-color: '#767682'                                   #Switch background when Off<br /> <br /> 

## HACS installation - recommended<br /> 
Works only for transparentgray.yaml<br /> 
1. Open HACS
2. Click the tree dots in the upper right
3. Click custom repositories
4. Add the URL of this github repo.
5. Go to frontend
6. Search for transparent dark gray
7. Click Install 
You should now be able to select "transparentgray-LAB" in Home Assistant. Maybe a restart of HA is required.<br /> 
"LAB" stands for "Lovelace Animated Background".

### Manual Installation - not recommended<br /> 
1. Download the transparentgray*.yaml file from this github repo. - Only one, not all!
2. Upload the downloaded file to your "themes" directory
3. Add the resource reference to your lovelace config<br /> 

You should now be able to select this theme in Home Assistant
<br />

#### Changing the background image<br />
Have a look [here](https://github.com/JOHLC/transparentblue#changing-the-background-image) <br /> 
