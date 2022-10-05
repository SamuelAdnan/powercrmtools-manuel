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
[Power Crm Register WebHook](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterWebHook.png?raw=true)Register webhook with output variables, $(powercrmwebhookName) and $(powercrmwebhookId)
### Interactive-WebAPI (selection based)
[Google](https://www.google.com)
<table style="width: 100%;border-collapse: collapse;">
  <tr style="border: 1px solid #dddddd; text-align: left;padding: 8px;">
    <th style="border: 1px solid #dddddd; text-align: left;padding: 8px;">Regular (input based)</th>
    <th style="border: 1px solid #dddddd; text-align: left;padding: 8px;">Interactive-WebAPI (selection based)</th>

  </tr>
  <tr style="border: 1px solid #dddddd; text-align: left;">
    <td style="border: 1px solid #dddddd; text-align: left;padding: 5px;">Power Crm Tools Installer <p style="font-style:italic;">A task to configure dependencies for Power Crm Tools.)</p></td>
        <td style="border: 1px solid #dddddd; text-align: left;padding: 5px;">[Power Crm Tools WebAPI Installer](#https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/webapiinstaller.png?raw=true)<p style="font-style:italic;">An interactive UI task to register step to webhook or service endpoint.</p></td>
  
  </tr>
  
  <tr style="border: 1px solid #dddddd; text-align: left;padding: 5px;">
    <td style="border: 1px solid #dddddd; text-align: left;padding: 5px;">[Power Crm Register WebHook](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterWebHook.png?raw=true)<p style="font-style:italic;"> Register webhook with output variables, $(powercrmwebhookName) and $(powercrmwebhookId)</p></td>
        <td style="border: 1px solid #dddddd; text-align: left;padding: 5px;">[Power Crm WebAPI Register Step](#https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/webapisteps.png?raw=true)<p style="font-style:italic;"> An interactive UI task to register step to webhook or service endpoint with output variable, $(powercrmstepId)..
</p></td>
    
  </tr>
  <tr  style="border: 1px solid #dddddd; text-align: left;padding: 5px;">
    <td style="border: 1px solid #dddddd; text-align: left;padding: 5px;">[Power Crm Service Endpoint Registration](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterServiceBusPipeline.png?raw=true)<p style="font-style:italic;">Register service endpoint with output variables $(powercrmendpointId) and $(powercrmendpointName).
 </p></td>
<td></td>
    
  </tr>
  
    </tr>
  <tr  style="border: 1px solid #dddddd; text-align: left;;">
  <td style="border: 1px solid #dddddd; text-align: left;;">[Power Crm Register Step](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterServiceBusPipeline.png?raw=true)<p style="font-style:italic;"> Register plugin step with output variable, $(powercrmstepId).
</p></td>
 <td></td>
   </tr>
  
  
  <tr  style="border: 1px solid #dddddd; text-align: left;padding: 5px;">
   <td style="border: 1px solid #dddddd; text-align: left;padding: 5px;">[Power Crm Register Image](https://github.com/SamuelAdnan/powercrmtools-manuel/blob/main/images/RegisterImagePipeline.png?raw=true)<p style="font-style:italic;">Register crm image. $(powercrmendpointName).
 </p></td>
 <td></td>
  
</table>

# Issues
For issues (https://github.com/SamuelAdnan/powercrmtools-manuel/issues).


# LinkedIn
[Linkedin](https://www.linkedin.com/in/adnan-samuel-16659418/)


# EULA
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

