## Deep Learning for Neuroimaging data
{:#neuro-team .anchor}
A group working on applied biomedical problems focused on large-scale multimodal neuroimaging data analysis.

### Our research
{%- assign recent_projects = site.projects | where_exp: 'project', 'project.path contains "_projects/neuro"' | where_exp: 'project', 'project.front_id' | sort: 'front_id' | reverse  %}
{%- include _main/research/make_project_containers.html projects=recent_projects %}
{% include _content/title_sliders_for_devices.html class='project-plate' containers=containers -%}

<div class="buttons-container-wrapper">
    <div class="buttons-container">
        <a class="neuro-more flat-button" href="/neuro/">More about ADASE Neuro group</a>
    </div>
</div>
{{--}}