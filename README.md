# Data for "Gay/Bi Dating App, Muslim Prayer Apps Sold Data on People’s Location to A Controversial Data Broker"

This contains the data for our story "[Gay/Bi Dating App, Muslim Prayer Apps Sold Data on People’s Location to A Controversial Data Broker](https://themarkup.org/privacy/2022/01/27/gay-bi-dating-app-muslim-prayer-apps-sold-data-on-peoples-location-to-a-controversial-data-broker)."

This is a list of the apps we found in a sample of location data we received from a former X-Mode employee. 

The data was sourced from 107 apps, with more than 50,000 points of location data from more than 20,000 unique advertising IDs collected from 140 countries during 2018 and 2019. About a quarter of the apps are no longer active, and none of the apps appear to contain X-Mode’s code anymore.

This is not a complete list of the apps that were selling data to X-Mode at the time.  

Questions? Write to us: [keegan@themarkup.org](mailto:keegan@themarkup.org) and [alfred@themarkup.org](mailto:alfred@themarkup.org)

# Data
[xmode-apps.csv](https://github.com/the-markup/xmode-apps/blob/master/xmode_apps.csv) - 15.9 KB. 108 rows. First row is the header (CSV).

## Data Dictionary 

<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: left;">
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>app</strong></td>
      <td>The app "handle."</td>
    </tr>
     <tr>
      <td><strong>app_name</strong></td>
      <td>The app name as it appeared in the app store. </td>
    </tr>
      <tr>
      <td><strong>responded_and_confirmed_to_have_ended_xmode_sales</strong></td>
      <td>If “TRUE”, the app publisher responded to our questions and confirmed to The Markup that it no longer sells location data to X-Mode.</td>
    </tr>
     <tr>
     <td><strong>platform</strong></td>
      <td>Which platform the app was running on.</td>
    </tr>
     <tr>
     <td><strong>active</strong></td>
      <td>Does the app store listing appear to be active?</td>
    </tr>
     <tr>
     <td><strong>category</strong></td>
      <td>The category that the app belongs to.</td>
    </tr>
     <tr>
      <td><strong>app_store_google</strong></td>
      <td>The URL of the Google Play app store listing. Some of these listings may no longer be active. </td>
    </tr>
     <tr>
      <td><strong>app_store_ios</strong></td>
      <td>The URL of the Apple iOS app store listing. Some of these listings may no longer be active. </td>
    </tr>
     
  </tbody>
</table>

## Licensing
Copyright 2022, The Markup News Inc.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.