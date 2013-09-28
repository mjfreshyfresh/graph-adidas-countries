Graph Analysis of Adidas Country accounts
==========

I find it fascinating to study social networks with graph analysis tools such as [Gephi](http://gephi.org). 

* Who is most important in the network? 
* What unusual accounts are present in the network?
* How are the accounts related? 
* What 'communities' are present? 
* What are the characteristics of each community? 

Numerous questions can be answered and valuable insights can be derived. Unfortunately you need a certain level of technical skill to collect, manipulate and visualize the data. 

I recently wrote a simple [Ruby Twitter Collector](https://github.com/mjfreshyfresh/twitter_collector) which makes it easy to collect data. I also came across an excellent [JavaScript GEXF viewer](https://github.com/raphv/gexf-js) by [@raphv](http://twitter.com/raphv) which makes it easy to view the data in a modern web browser.

For this example I searched on Twitter for Adidas Country specific accounts and then collected the Friends of those accounts. (Friends are accounts Adidas deemed valuable enough to follow)

Here are the 15 country accounts I examined:
* @adidasIndonesia
* @adidasRU
* @adidas_jp
* @adidasGR
* @adidasSingapore
* @adidasPL
* @adidas_ES
* @adidasCO
* @adidasph
* @adidasNZL
* @adidasJapanOG
* @adidasMY
* @adidasCL
* @adidas_ITA
* @adidasUS
