# VPNの使い方の手引き

## VPNとは

VPN（Virtual Private Network）は、インターネット上でセキュアな通信を行うための仮想的なネットワークです。<br/>
VPNを使用することで、自分のデバイスとVPNサーバーとの間に暗号化されたトンネルを作り、安全な通信と直接通信を実現することができます。<br/>
qqey.netはTailscaleとCloudflare Zero Trust，SoftEther VPNを使用してVPNを構築しています。

## 注意点

webページのみを閲覧する場合はVPNを使用する必要はありませんが，直接的な通信を行う場合はVPN Clientをインストールする必要があります。<br/>
また，VPNを利用するにはGitHubアカウントとGitHub Organization(qqey)のメンバーである必要があります。(加入したい場合は，Discordの#依頼チャンネルにてお問い合わせください。)<br/>

## Cloudflare Zero TrustでのVPNの設定方法

1. CloudFlare Warp Clientをインストールします。<https://1.1.1.1/>
2. Cloudflare Warp Clientを起動し，設定から「Cloudflare Zero Trust」を選択します。
3. 組織名「qqey」入力し、接続をクリックします。
4. GitHub OAuthでログインし、アクセスを許可します。
5. Cloudflare Zero TrustのVPNが接続され，qqey.netのサービスにアクセスできるようになります。

## TailscaleでのVPNの設定方法

1. Tailscale Clientをインストールします。<https://tailscale.com/download>
2. MultiNetworkの「qqey」を選択します。
3. TailscaleのVPNが接続され，qqey.netのサービスにアクセスできるようになります。
