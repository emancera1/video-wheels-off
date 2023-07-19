# Compositions API Requests


## SQL Query

```
select *  from `qtco-customer-support.prod.app_api_access_last_14_days` 
where (account_sid = 'ACfecd5668dfccc1bcb13195a261f5a305' or parent_account_sid = 'ACfecd5668dfccc1bcb13195a261f5a305') and uri="/Compositions"
order by timestamp desc 
 ```

## Query Result

![](Screenshots/queryresult.csv)

### Screenshot

![](Screenshots/queryresult.png)
