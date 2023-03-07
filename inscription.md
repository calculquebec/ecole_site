---
layout: base
---
# Inscription

## Tarifs

|                   |                   |                       | Préférentiel (avant {{ site.data.dates.fin_preferentiel }} )                                              | Régulier                                                              |
|----------------   |------------------ |-------------------    |------------------------------------------------------------------------   |--------------------------------------------------------------------   |
| Académique        | Avec hébergement  | Occupation simple     | {{ site.data.inscription.tarifs.academique.hebergement.simple.preferentiel }}$        | {{ site.data.inscription.tarifs.academique.hebergement.simple.regulier }}$        |
|                   |                   | Occupation double     | {{ site.data.inscription.tarifs.academique.hebergement.double.preferentiel }}$        | {{ site.data.inscription.tarifs.academique.hebergement.double.regulier }}$        |
|                   | Sans hébergement  |                       | {{ site.data.inscription.tarifs.academique.sans_hebergement.preferentiel }}$          | {{ site.data.inscription.tarifs.academique.sans_hebergement.regulier }}$          |
| Non-académique    | Avec hébergement  | Occupation simple     | {{ site.data.inscription.tarifs.non_academique.hebergement.simple.preferentiel }}$    | {{ site.data.inscription.tarifs.non_academique.hebergement.simple.regulier }}$    |
|                   | Sans hébergement  |                       | {{ site.data.inscription.tarifs.non_academique.sans_hebergement.preferentiel }}$      | {{ site.data.inscription.tarifs.non_academique.sans_hebergement.regulier }}$      |

**Notes:**
* Le forfait avec hébergement comprend 4 nuités, du lundi au vendredi et les repas, du mardi au vendredi.
* Le forfait sans hébergement comprend seulement les repas du midi, du mardi au vendredi.

<hr>

{%if site.data.dates.ecole_date_btw_str %}
<section class="special">
<ul class="actions stacked">
    <li><a href="{{site.data.inscription.url}}" class="button">Inscrivez-vous</a></li>
</ul>
</section>
{%endif%}
