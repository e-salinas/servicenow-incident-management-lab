# servicenow-incident-management-lab

I used ServiceNow Service Operations Workspace to handle a simulated Tier 1 support incident from intake through resolution. One employee’s wired desktop couldn’t reach the internet or a shared drive. I recorded the business impact, set impact and urgency, and took ownership of the Priority 4 ticket.

In the scenario, `ipconfig /all` showed a self-assigned `169.254.x.x` address and no default gateway. Testing with a known-good jack, laptop, and cable isolated the failure to the original jack’s network path. I recorded the findings in internal work notes and routed the incident to the Network group.

I documented the simulated switchport VLAN correction and the verification steps: confirm a valid DHCP lease and default gateway, then test internet and shared-drive access on the original jack. I marked the incident **Resolved – Permanent Fix Applied**.
