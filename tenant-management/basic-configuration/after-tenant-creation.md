# After Tenant Creation

The following list of parameters has to be configured after creating the Tenant.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Parameter value</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">mlogserverj.customlogpath.queryids</td>
      <td style="text-align:left">Add the new Tenant ID to the existing config parameter separated by a
        comma. (This is required to view the dashboard data). For example, if the
        existing value is <em>1001,1002,1003.</em> If the new Tenant ID is <em>1004</em>,
        then the new value for the parameter will be <em>1001,1002,1003,1004</em>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">tenant.instances</td>
      <td style="text-align:left">Add the new Tenant ID to existing config parameter separated by comma.
        For example, if the existing value is <em>1001,1002,1003.</em> If the new
        Tenant ID is <em>1004</em>, then the new value for the parameter will be <em>1001,1002,1003,1004</em>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">datamgmt.search.profile.attribute.id.&lt;&lt;TENANTID&gt;&gt;</td>
      <td
      style="text-align:left">Configure this field once the profile is created</td>
    </tr>
    <tr>
      <td style="text-align:left">sdh.qb.campaign_source.datastore.id.&lt;&lt;TENANTID&gt;&gt;</td>
      <td style="text-align:left">Configure this field once the datastore is created with RTE structure</td>
    </tr>
    <tr>
      <td style="text-align:left">datamgmt.search.profile.attribute.id.&lt;&lt;TENANTID&gt;&gt;</td>
      <td
      style="text-align:left">Configure this field once the profile is created</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>sys.emailtemplate.preview.</p>
        <p>gatewayfromemailid.&lt;&lt;TENANTNAME&gt;&gt;</p>
      </td>
      <td style="text-align:left">In config param sets configure this field</td>
    </tr>
    <tr>
      <td style="text-align:left">sys.emailtemplate.preview.senderid.&lt;&lt;TENANTNAME&gt;&gt;</td>
      <td
      style="text-align:left">In config, param sets configure this field</td>
    </tr>
  </tbody>
</table>

To configure dedicated Queues, please coordinate with imicampaign L2 team. They will help you configure dedicated Queues and other associated changes.

