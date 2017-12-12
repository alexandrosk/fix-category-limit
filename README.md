# fix-category-limit
Fix Magento Category limit reindexer.
This is a known bug 
https://github.com/magento/magento2/issues/8018


## Installation


`php bin/magento module:enable Notintyo_FixCategoryLimit`
`php bin/magento setup:upgrade`
`php bin/magento setup:di:compile`

Reindex, clear cache and your done!
