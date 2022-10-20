# Power Crm Tools
A devops pipeline utility for microsoft customer engagement(dataverse) to automate the regisration of:
<ul><li>Service endpoints</li><li>WebHooks</li><li>Plugin Steps</li><li>Plugin Images</li></ul>

There is regular way (input based) of using the tasks but there are also an interactive way to register plugin steps. <br />
The interactive way (you can select existing webhooks/service endpoints etc.) is totally optional but can very help full <br />
 to look up the register webhooks or endpoints, for example if regualr step or image registration fails due to bad input <br />you can use the interactive way to select step/image from webhook or service endpoints.<br />
Indeed the interactive way requires a bit more parameters but provides more flexibility in terms of usability.
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

[![SC2 Video](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/videolinkfile2.png?raw=true)](https://youtu.be/kDt3lm388UY)

start : 00:00
about extension : 00:18
about extensionused for: 00:24
purpose: 00:42
all tasks explanied: 00:01:33
regular pipeline start: 00:04:41
regular tasks- pipeline variables: 00:04:53
webhook registration: 00:06:26
crm tip attributes: 00:09:28
service endpoint registration: 00:10:57
crm tip images: 00:13:36
info interactive tasks: 00:14:44
interactive pipeline start: 00:15:10
interactive tasks - service connection:00:15:44
interactive tasks - pat token :00:17:13
interactive tasks - pipeline variables: 00:17:58
demo interactive pipeline - tasks: 00:0019:15
demo crm webhook (azure function): 00:22:51
demo crm service endpoint (bus - queue): 00:24:38
contact info: 00:26:58
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

