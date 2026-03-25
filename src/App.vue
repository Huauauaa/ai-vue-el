<template>
  <div class="min-h-screen bg-slate-100 text-slate-800 py-10">
    <main class="mx-auto max-w-4xl px-4">
      <el-card shadow="hover" class="!rounded-2xl">
        <template #header>
          <div class="flex items-center justify-between">
            <h1 class="text-2xl font-bold">Vite + Vue 3 + TypeScript</h1>
            <el-tag type="success">Element Plus + Tailwind CSS</el-tag>
          </div>
        </template>

        <div class="space-y-6">
          <p class="text-slate-600">
            项目已完成基础初始化，可直接开始业务开发。
          </p>

          <div class="grid grid-cols-1 gap-4 md:grid-cols-3">
            <el-card class="!border-emerald-200">
              <h2 class="text-lg font-semibold text-emerald-600">Vite</h2>
              <p class="mt-2 text-sm text-slate-600">极速开发体验与构建性能。</p>
            </el-card>
            <el-card class="!border-green-200">
              <h2 class="text-lg font-semibold text-green-600">Vue 3 + TS</h2>
              <p class="mt-2 text-sm text-slate-600">组合式 API 与类型安全开发。</p>
            </el-card>
            <el-card class="!border-sky-200">
              <h2 class="text-lg font-semibold text-sky-600">Tailwind CSS</h2>
              <p class="mt-2 text-sm text-slate-600">原子化样式快速搭建界面。</p>
            </el-card>
          </div>

          <div class="flex flex-wrap gap-3">
            <el-button type="primary">Primary</el-button>
            <el-button>Default</el-button>
            <el-button type="success">Success</el-button>
            <el-button type="warning">Warning</el-button>
          </div>
        </div>
      </el-card>
    </main>
  </div>
</template>
