安装Mojo
打开终端并安装modular命令行工具：

sh
curl -s https://get.modular.com | sh -
然后使用以下命令登录到您的Modular帐户：

sh
modular auth
现在您可以安装Mojo SDK：

sh
modular install mojo

bash_profile
# Mojo
echo 'export MODULAR_HOME="/Users/sonic/.modular"' >> ~/.bashrc
echo 'export PATH="/Users/sonic/.modular/pkg/packages.modular.com_mojo/bin:$PATH"' >> ~/.bashrc

版本
mojo --version

执行
mojo HelloWorld.mojo 

Build
mojo build hello.mojo
