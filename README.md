# RestrictDeskphoneinCCP
 Restrict Deskphone access from within CCP Settings

A sample code that shows how to restrict an agent from using a deskphone for taking calls on Amazon Connect CCP interface.

--

Agents use the Amazon Connect Contact Control Panel (CCP) to interact with customer contacts. It's how they receive calls, chat with contacts, transfer them to other agents, put them on hold, and perform other key tasks.
CCP, provides flexibility for agents to be able to receive customer calls on a desk phone instead of browser based built-in softphone. This feature is usually useful for agents who are working from remote locations and have low bandwidth connectivity to be able to take calls over the internet using the browser.
While this feature is very useful for the keeping the agents connected it also incur an extra cost for the outbound call being made. And hence, often there is a requirement from organizations to restrict agents from using deskphones from the CCP settings.
