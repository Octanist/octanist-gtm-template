# Octanist - Server-Side Client #

Turn leads into value – Octanist makes offline conversion tracking effortless and accessible for everyone.

The Octanist Client Template allows you to capture HTTP responses whenever you qualify a lead. Octanist will send one of the following statuses to the server container:  

- **`converted_lead`** – Won lead  
- **`qualified_lead`** – Qualified but not yet converted  
- **`unconverted_lead`** – Lost lead  

The Client Template captures these lead qualifications and sends them to the server, allowing you to modify them or forward them to other marketing platforms.  

- For a detailed guide, visit **[https://octanist.com/docs/server](https://docs.octanist.com/outgoing-integrations/gtm-server)**.  
- For support, reach out to **support@octanist.com**.  
- Create a free account at **[octanist.com](https://octanist.com)**.  

## How to use  

1. **Upload the Template**: Upload this GTM Client Template to your **Server-Side GTM container**.  
2. **Create a Client**: Set up a client using this Server-Side GTM template.  
3. **Create a Trigger**: Create a trigger with the Client "Octanist" to capture all data sent from Octanist to the server.  
4. **Add the Trigger**: Attach the trigger to an existing or new tag to send your Octanist values to any platform available in **Server-Side Google Tag Manager**.  
