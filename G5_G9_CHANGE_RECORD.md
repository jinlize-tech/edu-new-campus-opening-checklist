# G5/G9 产品修改记录

- 产品编号：$(@{number=96; product_id=JLZ-EDU-SK-078; chinese_name=新校区开办清单; english_name=New Campus Opening Checklist; repository_name=edu-new-campus-opening-checklist; repository_url=https://github.com/jinlize-tech/edu-new-campus-opening-checklist; product_type=Skill; category_code=08; category=08 校区标准化与多校区管理中心; description=新校区开办准备清单。; target_users=System.Object[]; core_input=校区定位、面积、班级数、人员、资质准备、设备、消防/安全、预算和开业节点; main_output=开办清单、责任矩阵、里程碑、证据要求、风险项和验收口径; product_risk=把清单当行政审批或遗漏地区合规; dedup_label=无明显重复; dedup_note=与新校区筹建计划区别：本产品是开业前准备与验收清单，不制定完整商业筹建方案。; development_status=Planned / 待研发; license=Apache-2.0; spec_version=1.0.0; workbuddy_status=PLANNED_FOR_WORKBUDDY}.product_id)
- 产品名称：新校区开办清单
- 基线：EDUCATION_BASELINE_V1.0.0
- 基线提交：$BaselineCommit
- 原版本：1.0.0
- 新版本：1.0.1

## 本次修改

1. 强化产品专属执行流程、输入核对和输出验收规则。
2. 新增 scripts/validate_input.js，实际检查必填字段、冲突、未确认数据和敏感信息。
3. 新增正常、缺失、冲突、敏感信息和非法JSON场景输入。
4. 测试升级为 T1–T7 分层并保存逐项检查结果。
5. 安装包加入 Apache-2.0 LICENSE 和 THIRD_PARTY_NOTICES.md。
6. 安装包升级为 1.0.1，加入许可证、第三方声明和输入校验脚本，保留 1.0.0 ZIP。
7. 按本产品冻结规格补充专属处理规则、输入到成果的核对矩阵和去重边界。

## 产品专属增强

- 核心任务：新校区开办准备清单。
- 主要风险：把清单当行政审批或遗漏地区合规
- 去重边界：与新校区筹建计划区别：本产品是开业前准备与验收清单，不制定完整商业筹建方案。

- 先明确标准版本、适用校区、检查范围、证据来源和例外条件。
- 按流程节点核对责任人、输入、完成标准、输出和升级机制。
- 区分现状证据、标准要求、差距、影响、整改动作和复验标准。
- 不代替机构作出处罚、人事、财务或行政批准决定。

## 运行边界

- 本地模型行为：NOT_RUNTIME_VERIFIED
- WorkBuddy平台验证：WORKBUDDY_VALIDATION_NOT_IN_SCOPE
- 本轮不执行上传、安装、审核或正式发布。
