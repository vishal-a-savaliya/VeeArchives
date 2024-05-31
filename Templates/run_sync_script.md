<%* 
const { execSync } = require('child_process'); 
const vaultPath = `"${app.vault.adapter.basePath.replace(/\\/g, '/')}"`;
const command = `cd /d ${vaultPath} && npx quartz sync`;
execSync(command);
%>