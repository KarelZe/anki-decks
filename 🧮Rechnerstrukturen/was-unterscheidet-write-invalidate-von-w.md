## Note
nid: 1627988573194
model: Basic-d7a3e
tags: 05_uebung, 05_uebung_rs, checklater
markdown: false

### Front
Was unterscheidet <b>Write-Invalidate</b> von
<b>Write-Update-Protokollen</b>?

### Back
<div>
  <div>
    <ul>
      <li>Write-Invalidate Protokoll
        <ul>
          <li>arbeitet auf Cacheline-Ebene
          <li>braucht nur ein Invalidate
        </ul>
      <li>Write-Update Protokoll
        <ul>
          <li>arbeitet auf Wort-Ebene
          <li>bei mehrmaliger Aktualisierung desselben Datums
          mehrere Update-Broadcasts nötig
        </ul>
    </ul>
  </div>
</div>
