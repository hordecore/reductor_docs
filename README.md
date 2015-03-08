# reductor_docs

# таких не существует

  url          domain           https   url_is_domain              ip        ipSubnet


    0               0               0               0               0               0	
    0               x               1               x               x               x
    0               x               x               1               x               x

  # 0 отсутствует, 1 - присутствует, x - без разницы
  
    url  domain           https   url_is_domain              ip        ipSubnet	куда_добавляем
      1       x               0               1               0               0 вычисленный домен в url_list
      1       x               0               1               1               0 вычисленный домен в url_list, ip в ip_https_list
      1       x               0               1               0               1 вычисленный домен в url_list, subnet ip_https_list
      1       x               0               1               1               1 вычисленный домен в url_list, ip и subnet в ip_https_list
      1       x               0               0               0               0 url в url_list
      1       x               0               0               1               0 url в url_list, ip в ip_https_list
      1       x               0               0               0               1 url в url_list, subnet в ip_https_list
      1       x               0               0               1               1 url в url_list, ip и subnet в ip_https_list
      1       x               1               0               0               0 url в url_list, вычисленный домен в https_list
      1       x               1               0               1               0 url в url_list, вычисленный домен в https_list, ip в ip_https_list
      1       x               1               0               0               1 url в url_list, вычисленный домен в https_list, subnet ip_https_list
      1       x               1               0               1               1 url в url_list, вычисленный домен в https_list, ip и subnet в ip_https_list
      0       1               0               x               0               0 домен в url_list
      0       1               0               0               1               0 домен в url_list, ip в ip_https_list 
      0       1               0               x               0               1 домен в url_list, subnet в ip_https_list
      0       1               0               0               1               1 домен в url_list, ip и subnet в ip_https_list
      1       x               1               1               0               0 вычисленный домен в url_list, https_list
      1       x               1               1               1               0 вычисленный домен в url_list, https_list, ip в ip_https_list
      1       x               1               1               0               1 вычисленный домен в url_list, https_list, subnet в ip_https_list
      1       x               1               1               1               1 вычисленный домен в url_list, https_list, ip и subnet в ip_https_list
      0       0               0               0               1               0 ip в ip_http_list, ip_https_list
      0       0               0               0               0               1 subnet в ip_http_list, ip_https_list
      0       0               0               0               1               1 ip и subnet в ip_http_list, ip_https_list
