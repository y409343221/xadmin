# xadmin
python3支持的xadmin

使用方法：
1. 把xadmin包拖到extra_apps目录下，把extra_apps mark为source root
2.主路由中
import xadmin

urlpatterns = [
    url(r'^xadmin/', xadmin.site.urls),
]

3. 在install_apps中注册xadmin即可


