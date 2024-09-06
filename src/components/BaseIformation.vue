<template>
    <el-descriptions class="margin-top" title="With border" :column="3" border>
        <template #extra>
            <el-button type="primary">Operation</el-button>
        </template>
        <el-descriptions-item>
            <template #label>
                <div class="cell-item">
                    <el-icon :style="iconStyle">
                        <user />
                    </el-icon>
                    Name
                </div>
            </template>
            Spark
        </el-descriptions-item>
        <el-descriptions-item>
            <template #label>
                <div class="cell-item">
                    <el-icon :style="iconStyle">
                        <iphone />
                    </el-icon>
                    Telephone
                </div>
            </template>
            18100000000
        </el-descriptions-item>
        <el-descriptions-item>
            <template #label>
                <div class="cell-item">
                    <el-icon :style="iconStyle">
                        <location />
                    </el-icon>
                    Years of Work
                </div>
            </template>
            7 Years+
        </el-descriptions-item>
        <el-descriptions-item>
            <template #label>
                <div class="cell-item">
                    <el-icon :style="iconStyle">
                        <tickets />
                    </el-icon>
                    Remarks
                </div>
            </template>
            <el-tag>School</el-tag>
        </el-descriptions-item>
        <el-descriptions-item>
            <template #label>
                <div class="cell-item">
                    <el-icon :style="iconStyle">
                        <office-building />
                    </el-icon>
                    Educational background
                </div>
            </template>
            University of Electronic Science and Technology of China
        </el-descriptions-item>
    </el-descriptions>
</template>

<script setup lang='ts'>
import {
    Iphone,
    Location,
    OfficeBuilding,
    Tickets,
    User,
} from '@element-plus/icons-vue'

const iconStyle = computed(() => {
    const marginMap = {
        large: '8px',
        default: '6px',
        small: '4px',
    }
    return {
        marginRight: marginMap.default,
    }
})

onMounted(() => { });

</script>

<style scoped lang="scss"></style>
