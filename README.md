# Power Crm Tools
A devops pipeline utility for autoamting the regisration of follwings into the microsoft customer engagement(dataverse):
<ul><li>Service end poionts</li><li>WebHooks</li><li>Plugin Steps</li><li>Plugin Images</li></ul>

More tasks in future.

# Compatibility
Dynamics365 9.0 (on-premises (azure aware)) <br />
Customer engagement online versions

# Parameters
OAUTH/ClientSecret Crm connection<br />

# Video


# Tasks

### Regular (input based)
Power Crm Tools Installer (A task to configure dependencies for Power Crm Tools)<br />
[Power Crm Register WebHook](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterWebHook.png?raw=true). Register webhook with output variables, $(powercrmwebhookName) and  $(powercrmwebhookId)<br />
[Power Crm Service Endpoint Registration](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterServiceBusPipeline.png?raw=true). 
Register service endpoint with output variables $(powercrmendpointId) and $(powercrmendpointName).<br />
[Power Crm Register Step](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterServiceBusPipeline.png?raw=true). Register plugin step with output variable $(powercrmstepId).<br />
[Power Crm Register Image](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterImagePipeline.png?raw=true). Register crm image to plugin, webhook or image.<br />

### Interactive-WebAPI (selection based)
[Power Crm Tools WebAPI Installer](#https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/webapiinstaller.png?raw=true)<p style="font-style:italic;">An interactive UI task to register step to webhook or service endpoint.<br />
[Power Crm Tools WebAPI Register Step](#https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/webapisteps.png?raw=true). An interactive UI task to register step with output variable $(powercrmstepId) .<br />
[Power Crm Tools WebAPI Register Image](#https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/webapiimage.png?raw=true). An interactive UI task to register image to plugin,webhook or service endpoint.<br />  

# Issues
For issues (https://github.com/SamuelAdnan/powercrmtools-manuel/issues).


# LinkedIn
[Linkedin](https://www.linkedin.com/in/adnan-samuel-16659418/)


# EULA
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

