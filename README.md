# totp-generator
##借用大佬[jaden](https://github.com/jaden/totp-generator)的源码

#1.添加了秘钥自动去除空格转化为大写字母。

##比如谷歌的秘钥：tsxw y3ro 4f4j 6sk2 mjgp kauq pt3z jbia

##粘贴进去会自动转化大写，为后期使用URL片段提供方便，

<img width="613" height="533" alt="image" src="https://github.com/user-attachments/assets/ece6320b-9342-4f07-982e-dc94142b0580" />


添加了使用说明
      <!-- 使用说明区域（移动到主程序下方，但在同一个容器内） -->
      <div class="box instructions-box">
        <h2 class="subtitle is-5">使用说明</h2>
        <div class="content is-small">
          <p>本工具用于生成基于TOTP算法的动态验证码，适用于两步验证场景（如谷歌账号、各类平台二次验证）。</p>
          <ul>
            <li><strong>密钥（Secret Key）</strong>：输入base32格式的密钥（通常在开启两步验证时获取）</li>
            <li><strong>位数（Digits）</strong>：验证码长度，默认6位（大多数平台使用）</li>
            <li><strong>周期（Period）</strong>：验证码有效期（秒），默认30秒（标准值）</li>
            <li>输入完成后，页面将自动生成动态验证码，点击右侧图标可复制到剪贴板</li>
            <li>验证码将随时间自动更新，进度条显示剩余有效时间</li>
			<li>您可以使用 URI 片段或查询参数在 URL 中提供密钥，例如https://2fa.bimi.eu.org/#/KEY或者https://2fa.bimi.eu.org?key=KEY</li>
          </ul>
        </div>
      </div>
