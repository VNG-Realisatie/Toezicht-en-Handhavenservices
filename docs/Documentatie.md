---
layout: page-with-side-nav
title: Documentatie StUF-BG
folder_files:
  - title: Koppelvlakspecificatie Keten Toezicht en Handhaven v0 9 6 (pdf)
    path: documenten/Koppelvlakspecificatie_Keten_Toezicht_en_Handhaven_v0_9_6.pdf
    group: 20
    versie: 0.9.6
    status: 
    omschrijving: 
    datum: 20140520
  - title: Koppelvlakspecificatie Toezicht en Handhaven - Berichtschema's (zip)
    path: documenten/Koppelvlakspecificatie_Toezicht_en_Handhaven_-_Berichtschema%27s.zip
    group: 20
    versie: 2.0
    status: Definitief
    omschrijving: 
    datum: 20140424
---

# Documentatie

## Toezicht- en Handhavenservices 2.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 20 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
