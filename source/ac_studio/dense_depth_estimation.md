# 稠密深度估计  
输入单帧图像和点云，通过 PromptDA 算法生成基于图像分辨率的稠密深度图。

以下视频提供了稠密深度估计离线演示效果，主要使用的硬件配置为：

<table class="docutils align-default">
    <tbody>
        <tr class="row-even">
            <td>计算平台</td>
            <td>Radxa ROCK5B+</td>
        </tr>
        <tr class="row-odd">
            <td>模型</td>
            <td>PromptDA-vitsmall（100M）</td>
        </tr>
        <tr class="row-even">
            <td>传感器</td>
            <td>AC1</td>
        </tr>
    </tbody>
</table>

<iframe style="margin-bottom: 24px;" width="100%" height="308" src="https://cdn.robosense.cn/AC_wiki/dense_depth_net_radxa.mp4" frameborder="0" allowfullscreen></iframe>

视频数据：[Library](https://cdn.robosense.cn/AC_wiki/dense_depth_net_demo.zip)

详细代码：[AC1 Dense Depth](https://github.com/RoboSense-Robotics//perception)

以下视频提供了同样场景离线演示效果，主要使用的硬件配置为：

<table class="docutils align-default">
    <tbody>
        <tr class="row-even">
            <td>计算平台</td>
            <td>CPU: Intel® Xeon(R) Gold 6230R CPU @ 2.10GHz x 104 <br> GPU: NVIDIA A40 <br> MEM: 64G </td>
        </tr>
        <tr class="row-odd">
            <td>模型</td>
            <td>PromptDA-vitlarge (1360M）</td>
        </tr>
        <tr class="row-even">
            <td>传感器</td>
            <td>AC1</td>
        </tr>
    </tbody>
</table>

<iframe style="margin-bottom: 24px;" width="100%" height="308" src="https://cdn.robosense.cn/AC_wiki/dense_depth_net.mp4" frameborder="0" allowfullscreen></iframe>  

视频数据：[Library](https://cdn.robosense.cn/AC_wiki/dense_depth_net_demo.zip)    

详细代码：[AC1 Dense Depth](https://github.com/RoboSense-Robotics//perception)   
