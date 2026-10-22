# NJUtable 表单助手

这个项目包含给 AI 助手使用的 Skill，以及给第一次使用在线表格的人看的图文说明。示例展示姓名、性别和文件上传；实际字段由使用者指定。

## 文件

- [nju-table-source.zip](nju-table-source.zip)：解压后可查看 `nju-table/` Skill 源文件、文字说明和原始截图。
- [nju-table.skill](nju-table.skill)：Skill 压缩包，可按当前客户端支持方式导入。
- [NJUtable_小白图解使用说明.docx](NJUtable_小白图解使用说明.docx)：13 页完整图文说明，红圈标出操作位置。
- 源码包内 `使用说明.md`：文字版步骤。完整红圈图解优先用 Word 说明阅读；Markdown 的 SVG 是否显示取决于查看器。

## 使用 Skill

下载并解压源码包后，将 `nju-table` 文件夹放入你使用的 AI 助手支持的技能目录，再按客户端说明刷新技能。不同客户端的安装方式可能不同。此包不会安装浏览器工具，也不包含登录信息。

可以这样提出任务：

> 使用 $nju-table，在我指定的站点新建收集表，字段为姓名、性别和附件，要求登录才能填写。先核对字段，完成后给我填写链接。

> 使用 $nju-table，按我提供的附件表头制作表单，保留字段顺序和特殊文字答案。只读取结构，不导入示例人员。

首次操作前，使用者自行打开目标站点并登录。助手只处理明确要求的表格和权限。独立运行还需要宿主提供可用的浏览器控制工具。

## 说明范围

图解依据既有空白示例界面整理，界面版本变化时以实际按钮为准。截图中展示的业务名称仅帮助识别控件。包内不含真实人员记录、账号密码、专属填写链接、原始业务附件和工作日志。

本仓库中的所有代码很有可能并不适用于你需要的场景, 不提供任何技术支持, 所有代码仅供交流学习使用, 使用代码导致的一切后果均由使用者自行承担.

该软件按“原样”提供，不提供任何形式的保证，无论是明示或暗示，包括但不限于适销性、特定目的的适用性和非侵权的保证。在任何情况下，无论是在合同行为、侵权行为或其他情况下，作者或版权所有者均不对任何索赔、损害或其他责任负责，无论是因使用或与软件或软件的其他交易有关的事项而产生或与之相关。

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
