<div align="center">
    <img src="https://kkaraivanov.github.io/favicon.ico" width="60px" />

##### <a href="https://kkaraivanov.github.io">kkaraivanov.github.io</a>

#### This is my portfolio project using React framework
<p style="text-align: justify">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The "appService.js" file writes a token object to the browser's local storage with a validity of three days to reduce the flow of requests to github and the object is used to represent my data later in the code.</p>

 ```javascript
export async function appServiceLoad() {
    if (getToken() == null) {
        // business logic

        if (token) {
            setToken(token);
            return true;
        }

        return false;
    } else {
        // business logic

        if (today > date) {
            clearToken();
            appServiceLoad();
        }
        return true;
    }
}
 ```
<p style="text-align: justify">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I have an idea to include a section to share projects and comments related to my Facebook profile. For this reason, I have included an additional file through which users can log in with their personal Facebook profiles and store the comments in a firebase database. Here's my on a quickly invented solution:</p>


 ```javascript
return (
    <appContext.Provider value={{
        user,
        setUser
    }}>
        <div className='app-background'>
            {!contextIsTrue && !error ? (
                <h3 style={{ color: 'black' }}>Loading...</h3>
            ) : !contextIsTrue && error ? (
                <Route><ServerDown /></Route>
            ) : (
                <>{props.children}</>
            )}
        </div>
    </appContext.Provider>
)
 ```

 <p style="text-align: justify">As yet i think what the contact form to he do - send email or message on facebook messenger. In the this moment she is do not work</p>

</br></br>
<div align="left">

<h2 style="display: inline-block;"> 

:star: 
</h2>
<p style="display: inline-block;">&nbsp;Click on the star. Thank your</p>
</div>

<br/><br/>
<p align="center">
  <a href="https://dotnet.microsoft.com/">
    <img src="https://www.vectorlogo.zone/logos/dotnet/dotnet-ar21.svg" alt="dotnet" style="vertical-align:top; margin:4px 10px;">
  </a>
  <a href="https://dotnet.microsoft.com/">
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/ee/.NET_Core_Logo.svg" height="60px" alt="dotnet" style="vertical-align:top; margin:4px 10px;">
  </a>
  <a href="https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor">
    <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Blazor.png" alt="Blazor" height="60px" style="vertical-align:top; margin:4px 10px">
  </a>
   <a href="https://reactjs.org/">
    <img src="https://www.vectorlogo.zone/logos/reactjs/reactjs-ar21.svg" alt="wordpress" style="vertical-align:top; margin:4px 10px">
  </a>
  <a href="https://hub.docker.com/">
    <img src="https://www.vectorlogo.zone/logos/docker/docker-ar21.svg" alt="docker" style="vertical-align:top; margin:4px 10px">
  </a> 
  <a href="https://code.visualstudio.com">
    <img src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-ar21.svg" alt="vs-code" style="vertical-align:top; margin:4px 10px">
  </a>
  <a href="https://www.postman.com">
    <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-ar21.svg" alt="postman" style="vertical-align:top; margin:4px 10px">
  </a>
  <a href="https://www.github.com">
    <img src="https://www.vectorlogo.zone/logos/github/github-ar21.svg" alt="github" style="vertical-align:top; margin:4px">
  </a>
  <a href="https://www.git.com">
    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg" alt="git-scm" style="vertical-align:top; margin:4px">
  </a>
</p>

<br/><br/>
<div align="center">
<a href="#"><img src="https://github-profile-trophy.vercel.app/?username=kkaraivanov&row=1"></a>
</div>
