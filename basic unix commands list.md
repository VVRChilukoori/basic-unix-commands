<p>In this environment my home directory location is&nbsp;<strong>/home/cloudera</strong>. Below codes have to be entered into the terminal.</p>
<p><strong>Note*:</strong> Home directory will not be same for everyone.&nbsp;</p>
<p>&nbsp;</p>
<table>
<tbody>
<tr>
<td width="312">
<p>echo hello world</p>
</td>
<td width="312">
<p>Print &ldquo;<strong>hello world</strong>&rdquo; to the standard output.</p>
</td>
</tr>
<tr>
<td width="312">
<p>pwd</p>
</td>
<td width="312">
<p>Print the working directory.&nbsp; We&rsquo;re in &ldquo;<strong>~</strong>&rdquo; which we know is the user&rsquo;s home directory, but this will give you the full address: <strong>/home/cloudera</strong></p>
</td>
</tr>
<tr>
<td width="312">
<p>ls</p>
</td>
<td width="312">
<p>List files and folders in the working directory.</p>
</td>
</tr>
<tr>
<td width="312">
<p>ls -l</p>
</td>
<td width="312">
<p>The same, but with details.</p>
</td>
</tr>
<tr>
<td width="312">
<p>ls -a</p>
</td>
<td width="312">
<p>The same, but with hidden files included.</p>
</td>
</tr>
<tr>
<td width="312">
<p>ls -al</p>
</td>
<td width="312">
<p>The same, but with details <em>and</em> hidden files.</p>
</td>
</tr>
<tr>
<td width="312">
<p>ls /</p>
</td>
<td width="312">
<p>List files in the top level directory of the file system.</p>
</td>
</tr>
<tr>
<td width="312">
<p>cd /</p>
</td>
<td width="312">
<p>Change directory to &ldquo;<strong>/</strong>&rdquo;.</p>
</td>
</tr>
<tr>
<td width="312">
<p>cd home</p>
<p>cd cloudera</p>
</td>
<td width="312">
<p>From the top level, cd into the &ldquo;home&rdquo; directory and then the &ldquo;cloudera&rdquo; subdirectory.&nbsp; These are <em>relative</em> moves because you didn&rsquo;t enter the full address of either directory.</p>
</td>
</tr>
<tr>
<td width="312">
<p>mkdir testdir</p>
</td>
<td width="312">
<p>Make a directory called &ldquo;<strong>testdir</strong>&rdquo; within the current working directory.</p>
</td>
</tr>
<tr>
<td width="312">
<p>cd /home/cloudera/testdir</p>
</td>
<td width="312">
<p>Move into testdir by providing the <em>absolute</em> location of it.&nbsp; You could also have just used &ldquo;<strong>cd testdir</strong>&rdquo;.</p>
</td>
</tr>
<tr>
<td width="312">
<p>cd ~</p>
</td>
<td width="312">
<p>Move back to the home directory.</p>
</td>
</tr>
</tbody>
</table>
