{% highlight bash %}
curl https://api.clarify.io/v1/bundles/abcde12345/insights/34567abcde \
    --header "Authorization: Bearer myapikey" \ | jq '.track_data[0].topics[0].categories[0].path[]'
# The jq portion is optional and just used to extract the resulting topic tree
{% endhighlight %}