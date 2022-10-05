# Power Crm Tools
A devops pipeline utility for microsoft customer engagement(dataverse) to automate the regisration of:
<ul><li>Service endpoints</li><li>WebHooks</li><li>Plugin Steps</li><li>Plugin Images</li></ul>

There is regular way (input based) of using the tasks but there are also an interactive way to register plugin <br />
steps. The interactive way (you can select existing webhooks/service endpoints etc.) is totally optional but can<br />
help very full to look up the register webhooks or endpoints, for example if regualr step or image registration fails due to bad input you can use the interactive way to select step/image from webhook or service endpoints.<br />
Indeed the interactive way requires a bit more parameters but provides more flexibility in terms of usability.
[more detail images](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/README.md)<br />
<i>More related tasks coming as well.</i>

# Compatibility
Dynamics365 9.0 (on-premises (azure aware)) <br />
Customer engagement online versions

# Parameters
OAUTH/ClientSecret Crm connection<br />
Both Power Crm Register WebHook and Service Endpoint, provides output variables to be used in next tasks.<br />
Interactive tasks, PAT and Service connection name.<br />
see videos more full detail.

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
[Power Crm Tools WebAPI Installer](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/webapiinstaller.png?raw=true). An interactive UI task to register step to webhook or service endpoint.<br />
[Power Crm Tools WebAPI Register Step](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/webapisteps.png?raw=true). An interactive UI task to register step with output variable $(powercrmstepId) .<br />
[Power Crm Tools WebAPI Register Image](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/webapiimage.png?raw=true). An interactive UI task to register image to plugin,webhook or service endpoint.<br />  

# Issues
For issues (https://github.com/SamuelAdnan/powercrmtools-manuel/issues).


# LinkedIn
[Adnan Samuel](https://www.linkedin.com/in/adnan-samuel-16659418/)


# EULA
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

