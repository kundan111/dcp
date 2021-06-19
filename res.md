<p style="margin-top: 0; color: #555; font-size: 16px; line-height: 1.5em; text-align: left; font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif; box-sizing: border-box;">Good morning! Here's your coding interview problem for today.</p>
<p style="margin-top: 0; color: #555; font-size: 16px; line-height: 1.5em; text-align: left; font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif; box-sizing: border-box;">This problem was asked by Google.</p>
<p style="margin-top: 0; color: #555; font-size: 16px; line-height: 1.5em; text-align: left; font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif; box-sizing: border-box;">Implement a <code style="font-family: monospace; margin: 0 2px; padding: 0 5px; white-space: nowrap; border: 1px solid #eaeaea; background-color: #f8f8f8; border-radius: 3px;">PrefixMapSum</code> class with the following methods:</p>
<ul style="text-align: left; color: #555; font-size: 16px; line-height: 1.5em; padding-left: 24px; font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif; box-sizing: border-box;">
<li style="font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif; box-sizing: border-box;"><code style="font-family: monospace; margin: 0 2px; padding: 0 5px; white-space: nowrap; border: 1px solid #eaeaea; background-color: #f8f8f8; border-radius: 3px;">insert(key: str, value: int)</code>: Set a given key's value in the map. If the key already exists, overwrite the value.</li>
<li style="font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif; box-sizing: border-box;"><code style="font-family: monospace; margin: 0 2px; padding: 0 5px; white-space: nowrap; border: 1px solid #eaeaea; background-color: #f8f8f8; border-radius: 3px;">sum(prefix: str)</code>: Return the sum of all values of keys that begin with a given prefix.</li>
</ul>
<p style="margin-top: 0; color: #555; font-size: 16px; line-height: 1.5em; text-align: left; font-family: Arial, 'Helvetica Neue', Helvetica, sans-serif; box-sizing: border-box;">For example, you should be able to run the following code:</p>
<pre style="background-color: #f8f8f8; border: 1px solid #cccccc; font-size: 13px; line-height: 19px; overflow: auto; padding: 6px 10px; border-radius: 3px;"><code class="lang-python" style="border-radius: 3px; font-family: monospace; margin: 0; padding: 0; white-space: pre; background: transparent; background-color: transparent; border: none;">mapsum.insert("columnar", 3)

assert mapsum.sum("col") == 3



mapsum.insert("column", 2)

assert mapsum.sum("col") == 5

</code></pre>
