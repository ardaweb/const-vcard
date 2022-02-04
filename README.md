### CONST VCARD 2 KONTAK

<a href="ARDA SAHA"><img src="https://i.ibb.co/3sNqZ3w/Screenshot-2022-02-04-23-52-22-12-bffcc91240b98183b312fa568184e694.jpg" alt="ArdaStore" border="0"></a>

```const-vcard
{
let ini_list = []
for (let i of ownerNumber) {
var vname = xdev.contacts[i] != undefined ? xdev.contacts[i].vname || xdev.contacts[i].notify : undefined
ini_list.push({
"displayName": `ArdaStoreゑ`,
"vcard": `BEGIN:VCARD\n
VERSION:3.0\n
N:Sy;${nSy};;;\n
FN:${vname ? ` ${vcardName}` : ` ${vcardName2}`}\n
ORG:${vcardinfo};\n
URL;⚙️ WEB:${urlWebsiteVcard}\n
EMAIL;📧 Email: ${emaildiVcard}\n
item4.ADR:;;${regionVcard};\n
item4.X-ABLabel:🌍 Region\n
item1.X-ABLabel:${deskVcard1}\n
TEL;${deskripppsi};waid= ${nomorvcard1}:${nomorvcard1}\n
item1.TEL;${deskripppsi};waid=${nomorvcard22}:${nomorvcard22}\n
item1.X-ABLabel:${deskVcard3}\n
END:VCARD`
})
}
xdev.sendMessage(from, {"displayName": `ArdaStoreゑ`,"contacts": ini_list }, 'contactsArrayMessage', { quoted: dev, contextInfo: { forwardingScore: 508, isForwarded: true }})
```
