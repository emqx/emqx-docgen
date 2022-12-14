# License

## key_license <a id='key_license'></a>
License provisioned as a string.

| Config paths | Env overrides |
|----------------------|---------------------------|
|  <code>license</code> | <code>EMQX_LICENSE</code>  |


**Fields**

<ul class="field-list">
<li>
<h4>key</h4>
License string

<table>
<tbody>
<tr><td><strong>Type</strong></td><td><code>binary()</code></td></tr><tr><td><strong>Default</strong></td><td><code>"MjIwMTExCjAKMTAKRXZhbHVhdGlvbgpjb250YWN0QGVtcXguaW8KZGVmYXVsdAoyMDIyMDQxOQoxODI1CjEwMDAK.MEQCICbgRVijCQov2hrvZXR1mk9Oa+tyV1F5oJ6iOZeSHjnQAiB9dUiVeaZekDOjztk+NCWjhk4PG8tWfw2uFZWruSzD6g=="</code></td></tr></tbody>
</table>
</li>
<li>
<h4>connection_low_watermark</h4>
Low watermark limit below which license connection quota usage alarms are deactivated

<table>
<tbody>
<tr><td><strong>Type</strong></td><td><code>emqx_schema:percent()</code></td></tr><tr><td><strong>Default</strong></td><td><code>"75%"</code></td></tr></tbody>
</table>
</li>
<li>
<h4>connection_high_watermark</h4>
High watermark limit above which license connection quota usage alarms are activated

<table>
<tbody>
<tr><td><strong>Type</strong></td><td><code>emqx_schema:percent()</code></td></tr><tr><td><strong>Default</strong></td><td><code>"80%"</code></td></tr></tbody>
</table>
</li>

</ul>
